##fastbooks
##### Personal expense tracking web application

### Overview
The simple-to-use, minimalist --but entirely adequate for being aware and careful about spending  -- application ("fastbooks") will allow multiple users to track all of their expenditures (where their money goes), categorize the expenses, track and reconcile credit card and other "bank" transactions.

### Features
Each user can do the following:
1. SIGN UP, LOG IN: Sign up and, thereafter, log in (via passwords, not OAuth)
2. Add, edit, and delete EXPENSE items: date, amount, vendor, item, expense category
3. Add, edit, and delete EXPENSE CATEGORIES, one of which is assigned to each expense item
4. Add, edit, delete, and reconcile BANK ITEMS, one of which (credit card, PayPal, VenMo, check issuance, etc.) could cover multiple expense items. This functionality is the means to reconcile periodic statements from the financial entity, ensuring that all transactions have been recorded as expenses.
5. Add, edit, delete BANKS, i.e., financial institution or organization to be assigned to each BANK ITEM
6. Use an API to get sales tax rates, for the purpose of determining correct per-item sales tax amounts when breaking a transaction into multiple EXPENSE items.
7. Run searches and generate reports (pdf?) for specifiable time intervals.
8. Admin role will control permission (issue initial passwords?) to users to use the service.

### Technologies
*flask
*Python
*Bootstrap
*MySQL
*SQLAlchemy
*React
*Apache or nginx web server
*AWS EC2 instance or Digital Ocean droplet
*git, GitHub
*Pivotal

### What I'll Have to Learn
How to configure React on cloud server
