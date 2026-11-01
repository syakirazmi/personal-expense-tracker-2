# User Stories

## US1 – Record Income

As a user, I want to record my income transactions, so that I can keep track of the money I receive.

**Related Requirements:** FR1, FR4

**Acceptance Criteria:**
1. Given that the user enters a valid income amount, description, category and date, when the user saves the transaction, then the system shall store the income record.
2. Given that an income transaction has been saved, when the user views the transaction list, then the system shall display the recorded income details.

## US2 – Record Expenses

As a user, I want to record and categorise my expenses, so that I can monitor where my money is being spent.

**Related Requirements:** FR2, FR4

**Acceptance Criteria:**
1. Given that the user enters a valid expense amount, description, category and date, when the user saves the transaction, then the system shall store the expense record.
2. Given that an expense transaction has been saved, when the user views the transaction list, then the system shall display the expense details and assigned category.

## US3 – View Financial Summary

As a user, I want to view my total income, total expenses and remaining balance, so that I can understand my current financial situation and manage my spending effectively.

**Related Requirements:** FR5

**Acceptance Criteria:**
1. Given that income and expense transactions have been recorded, when the user opens the financial summary, then the system shall display the total income and total expenses.
2. Given that financial transactions have been recorded, when the user views the remaining balance, then the system shall calculate it by subtracting total expenses from total income.