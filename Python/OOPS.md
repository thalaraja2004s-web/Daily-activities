from abc import ABC, abstractmethod


class Payment(ABC):

    @abstractmethod
    def pay(self, amount):
        pass


class CreditCard(Payment):

    def pay(self, amount):
        print("Paid", amount, "using CreditCard")


class UPI(Payment):

    def pay(self, amount):
        print("Paid", amount, "using UPI")


# Get input from user
amt = int(input("Enter Amount: "))
ch = input("Enter Choice (CreditCard / UPI): ")

# Choose payment method
if ch == "CreditCard":
    p = CreditCard()

elif ch == "UPI":
    p = UPI()

else:
    print("Invalid Choice")
    exit()

# Make payment
p.pay(amt)
