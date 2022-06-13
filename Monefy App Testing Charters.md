#Monefy Android App Test Charters
## Charter 
    Explore the application to discover how expense/income is added, modified and deleted in the application
### Priority
High
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
System is not allowing negative values. 

System is allowing decimal values up to 2 decimals.

System is not allowing to add a expense with zero(0) amount.

User is allowed to enter an amount of 9 digits with or without decimals.

Repeat icon at the header is redirecting to get a pro version.

User can leave/resume from the same 'New Expense' screen. 

User is not allowed to add a new expense categroy in free version of the application.

User is able to select datetime of choice, enter amount, select the desired account, add notes related to that expense then it can choose category and add the expense.

Added new expenses of a single digit amount and 9 digit amount with decimals. System is correctly reflecting it on Main screen within pie chart.

Added new expenses with different accounts (Cash and Payment Card)

Added a expense can be modified/updated successfully from Balance screen having list of expenses.

Added a expense can be deleted successfully from Balance screen having list of expenses.

#### Suggestion/Improvement(s)
Input textfield for 'Notes' should be multiline and there should be a character limit on it.

A reset button is required to clear the amount at once. Currently, user has to tap cancel number of times of digits to clear them.

### Data files:
  Testing heuristics sheet for different types of inputs.
### Issues:
  
#

## Charter 
    Explore the budget mode on the application to discover how it works
### Priority
High
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
Budget Mode can be enabled from Setting and User have to add a 'Monthly Budget Amount' to start.

Budget amount should be a positive value upto 10 digits.

It can be updated to a new amount by clicking the amount next to 'Budget Mode' checkbox in Settings section.

Budget mode can be disabled successfully. 

If Budget mode is enabled the expenses amount is being deducted from budget amount to show the balance amount else expenses are deducted from the income amount to show balance amount.

#### Suggestion/Improvement(s)

### Data files:
  Testing heuristics sheet for different types of inputs.
### Issues:

#
## Charter 
    Explore the search and filter option to discover that results are accurately visible to user 
### Priority
High
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
User is able to search using category name and also modify/delete the added income/expense.

User is able to switch between different accounts from Menu. Data which is visible on home screen according to selected account accurately.

User is able to set range for the data to be visible on home screen.

#### Suggestion/Improvement(s)

### Data files:
  
### Issues:

#
## Charter 
    Explore the accounts setting to discover how to use multiple accounts
### Priority
Medium
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
User is able to add multiple accounts and use them while adding expenses.

User is able to filter records according to selected account with respect to date/week/month/year.

User is able to enable/disable any account.

User is able to merge an account into another account.

User is able to delete an account.

#### Suggestion/Improvement(s)
### Data files:
### Issues:



## Charter 
    Explore the Transfer feature to discover how to transfer amount between 02 accounts
### Priority
Medium
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
    User is able to transfer amount between 02 different account.
    System is not allowing user to transfer to same account. Valid.
    System has no validation on the amount which can be transferred to eachother.
#### Suggestion/Improvement(s)
    If an account has 4000 EUR in Balance then User should not be allowed to transfer more than 4000 EUR to other account.
### Data files:
  
### Issues:
    

## Charter 
    Explore the Currencies feature to discover how to change currency
### Priority
Medium
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
    User is able to change the currency type in the settings.
    Currency is being updated through all the application.

#### Suggestion/Improvement(s)
    Users have different currency accounts. An option can be provided to update currency for all accounts or specific accounts.
### Data files:
### Issues:



## Charter 
    Explore the settings to discover how take backup and restore the data
### Priority
Low
### Tester:
Farrukh Dilawar
### Duration:
30 min
### Test Notes:
#### Findings
    User is able to export the data to a file successfully.
    User is able to clear the data and then restore the data from exported file successfully.
    User is able to export/restore large data files successfully.
#### Suggestion/Improvement(s)
### Data files:
### Issues:
