Problem statement
1. Use python to create a program for a cashier machine.
2. The program will log entries of total cash received by calculating total number of units of different denominations.
3. In the same way machine can return balance by calculating total number of units of different denominations.
4. Machine would be able to log all transaction in the day and print a report at the end of day.



Steps followed
1. Created a function that will have the following.
  i. A list with all available denominations of currency in it.
  ii. A for loop that will iterate through the denomination list and take input from
      user for each denomination how many notes or coins were accepted/given and 
      return a total of money received/given.  
2. Created two lists 'Credits and 'Debits' to log in the credit and debit amount accordingly
   and a variable 'Beginning balance' to check the balance at the beginning and closing of the day.
3. A while loop to keep the program running as long as the user wants. 
4. If-else statement coupled with while loop to throw user an error when an invalid input 
   is received.  
