# Excel money tracker

This is an Excel money and budget tracker/planner. Tells you what you can safely spend every week.

# Quick start guide

## Step 1

Download *Budget.xlsx*.

> **Note:** upon first opening it, you must enable External Data Connections.
This is an internal query made with Power Query to filter out 'Primary' income from 'Secondary' income and sorting it by date. You can see this in the hidden tab *MainIncomeTable*.
This will change in a future update.

## Step 2

Fill out the following tabs as instructed.

**Income**

This tab contains your paydays, past and future. Fill in the date you were paid (or will be paid) and enter an exact amount.

You must specify whether the income is *Primary* or *Secondary* under the *Income type* column.

 - Primary: this is your main income, such as your monthly wage or quarterly student loan
 - Secondary: any other form of extra income

> **Important:** you must click 'Data' > 'Refresh All' for the changes to be applied

For simplicity, *Spread* is not explained here.
 
**Recurring**

Enter any payments that repeat every period.

You will have to enter separate rows for each period as shown below.

|Date|Description|Amount|
|--|--|--|
|05/03/2022|Gym membership|£20|
|...|...|...|
|05/04/2022|Gym membership|£20|
|...|...|...|
|05/05/2022|Gym membership|£20|


**One-offs**

Any unplanned spendings that are funded from outside the budget.

These spendings are 'bad', thus the red colour. These spendings are also highlighted in the *Allowance* tab under the column *Overspend*.

**Allowance**

Adjust the dates to the days you want to pay yourself your allowance (e.g. every Monday).

 - The *Max allowance* column changes dynamically according to how much money there is leftover.
 - The *Allowance paid* column is to be filled by you when you have paid yourself.


# Modifying the spreadsheet

You can change the spreadsheet any way it suits you.

All cells containing formulas are protected. You can unprotect them by going to 'Review' > 'Unprotect Sheet'. There is no password.

If you want to re-publish this anywhere, please credit the original developer (me).

# Documentation

As of today, I have not yet written any more documentation on this spreadsheet. Please bear with me as I want to write good documentation for this.

I will edit this as soon as I got something.
