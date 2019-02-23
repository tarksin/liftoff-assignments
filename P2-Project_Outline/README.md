# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
The application ("fastbooks") will allow multiple users to track all of their expenditures (where their money goes), and related information.

### Features
Each user can do the following:
1. Sign up and, thereafter, log in (via passwords, not OAuth)
2. Add, edit, and delete EXPENSE items: date, amount, vendor, item, expense category
3. Add, edit, and delete EXPENSE CATEGORIES, one of which is assigned to each expense item
4. Add, edit, delete, and reconcile BANK ITEMS, one of which (credit card, PayPal, VenMo, check issuance, etc.) could cover multiple expense items. This functionality is the means to reconcile periodic statements from the financial entity, ensuring that all transactions have been recorded as expenses.
5. Add, edit, delete BANKS, i.e., financial institution or organization to be assigned to each BANK ITEM
6. Use an API to get sales tax rates, for the purpose of determining correct per-item sales tax amounts when breaking a transaction into multiple EXPENSE items.
7. Manager role will issue permission (initial passwords?) to users to use the service.

### Technologies
flask
Python
Bootstrap
MySQL
React
Apache or nginx web server
AWS EC2 instance or Digital Ocean droplet

### What I'll Have to Learn
How to configure React on cloud server
