# Budgeting App

### An app to calculate your monthly budget
---

This is a budgeting app that takes in the total of your income and expenses and calculates budget.

It's done with vanilla javascript and uses controllers with IIFEs that communicate with each other. There's an over all Global controller that controls the Budget Controller and the UI controller.

What the app does:

* Shows the current month at the header
* Takes in 3 entries from the user
    * the + or - Operator for income/expense
    * Description for income/expense
    * Value
* The income and expenses are displayed below beased on the entries and the totals are calculated and displayed at the heading
* The expenses show a percentage based on the income and total percentage of expenses and the individual entries are displayed by its side
* On hovering over the entries it shows an X where you can delete any of the income or expenses and the totals at the header are automatically adjusted

This app has helped me learn a lot about closures, IIFEs and some fundamentals of vanilla JS.