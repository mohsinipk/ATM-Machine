# ATM-Machine

![Alt text](assets/images/UML.png "UML Diagram")

## Abstract
The ATM System is the project which is used to access their bank accounts in order to make cash
withdrawals. Whenever the user need to make cash withdraws, they can enter their PIN number
(personal identification number) and it will display the amount to be withdrawn in the form of 50’s,100’s
and 500’s. Once their withdrawn was successful, the amount will be debited in their account.

## Objective
Our main objective is to speed up the transactions done by customers. No manual transactions needed
generally. The second objective is to save the time which is very important now-a-days. It will include
other objectives such as:

• To render accurate services to customer.

• The reduction of fraudulent activities

• To achieve speedy processing of customer data

• To reduce error processing, the guarantee of increase security 

## Working
In order to develop an Automatic Teller Machine, you need to implement the following classes:
1. ATM
2. Basic Unit ATM
3. Complex ATM
4. User
5. Bank Account
6. Saving Account
7. Checking Account
8. Card

### Card:
  • CardNumber (int)
  • PIN (int)

Create a function that will automatically generate a card number for the user using rand function.

### BankAccount:
  • BankName (char*)

  • Branch (char*)

  • TotalCash (float)

### SavingAccount:
  • interestRate(float)

It also have a function to calculate the interest.

### CheckingAccount:
  • fee per transaction(float)

### User:
  • Name (char*)

  • PhoneNumber (int*)

  • Address (char*)

### ATM:
  • Take input (Card_number and PIN) from user.

  • Validate the Card number and pin entered by user.
