# mailroom_madness
A short app that sends emails to donors thanking them for their donations.

"""The following is pseudocode to outline our eventual app."""

donors = {'donors': '[individual donations]'}


def thank_you():
        full_name = prompt("Please select an option: L for list of donors and Q for quit. Otherwise, please enter the donor's full name? ")
        if full_name == 'Q':
            break
        elif full_name == 'list':
            return donors.keys()
        elif full_name not in list:
            donors[full_name] = value
            email = "Thank you, {}, for your generous donation of {}.".format(full_name, donors[full_name])
        elif full_name in list:
            amount = prompt("What amount would you like to donate? ")
            if amount isint:
                donors[full_name] += amount
            else:
                amount = prompt("What amount would you like to donate? ")
            email = "Thank you, {}, for your generous donation of {}.".format(full_name, donors[full_name])
        else:
            user_option_menu = prompt("Sorry, that's not a valid option. Please select a valid option: L for list of donors or Q for quit.")

        
def report():
    if ask_donors.lower() == 'report':
        for d in donors:
            print("{}: {}, {}, {}").format(full_name, sum([amount_donated]), len(amount_donated), sum([amount_donated])/ len(amount_donated))
        full_name = prompt("What is the donor's full name? ")
    else:
        user_option_menu = prompt("Sorry, that's not a valid option. Please select a valid option: L for list of donors, H for help menu, and Q for quit.")


def total_function():
    ask_donors = prompt("Thank you or Report ")
        if ask_donors.lower() == 'thank you':
            thank_you()
        elif ask_donors.lower() == 'report':
            report()

