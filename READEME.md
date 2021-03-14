Notes: 

1. ValidTime implemented in days, you pass in the daysAfter then the valid time is: now + daysAfter
2. All the charges and expenses are in "ether"
3. In payDivident(): otherExpenses is the sum of fixedExpenses + driverSalary if not paid since their specified peroid
4. Driver salary defined in the constructor 
5. Double joining is prevented
6. When to sell a car through purchasePropose() the user does not enter the carId because there is a single car if vailable so, use it directly
7. All exceptions are checked through require() and a proper message is printed in case of failure 
