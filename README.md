USER
-----
User_ID (PK)
Name
Email
Phone
Password
      |
      | 1 : N
      |
LOAN
-----
Loan_ID (PK)
User_ID (FK)
Loan_Amount
Loan_Type
Interest_Rate
Loan_Status
      |
      | 1 : N
      |
PAYMENT
--------
Payment_ID (PK)
Loan_ID (FK)
Payment_Amount
Payment_Date
Payment_Status