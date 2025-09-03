#Personal Finance data base and visuls

This project is made up of a database in excel that has 3 sheets. Credit cards which holds the name of the cards, bank, apr, and open date. Transactions which holds transactions, their dates, the card it was made on as well as the amount. The final sheet is monthlybalances which has the balance of my debt, minimum payments made, balaces as well as staement dates.
This is important for setting up a data base because Power Bi will pull everything directly from the excel sheet and even find corresponding data. Once my data was uploaded to Power Bi i created a few visuals. the first one shows my debt in a pie chart, with a splicer to highlight the piece of the pie that corresponds with the debt. The other visual is for my monthly payments, For this one i included a splicer that 
shows which banks are getting which amount. 

##To use:
Feel free to remove my data from the excel sheets and put your own data in the specified sheets. Once you do you can upload your excel database to Power BI and from there you will be able to see the following.
1. Balances by card
   a. Click a bar chart visual.
   b. Drag CreditCards[CardName] to the Axis.
   c. Drag MonthlyBalances[Balance] to Values.
3. Balance Trend over time
   a. Click a line chart.
   b. Drag MonthlyBalances[Month] to X-Axis.
   c. Drag MonthlyBalances[Balance] to Values.
   d. Drag CreditCards[CardName] to Legend.
5. Purchases vs. payments
   a. Click a stacked column chart.
   b. Drag Transactions[TransactionDate] to the X-Axis.
   c. Drag Transactions[Category] to Legend.
   d. Drag Transactions[Amount] to Values.

#You can add slicers to the project which will help highlight specific things in the visuals. If requests come along i can add more information on them. 

##requirements 
1. excel to use my excel database.
2. Power Bi to create visuals
   
project updated on: 2025-09-03
