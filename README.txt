# codeTest
1- Code looks good but I made few changes (BookingController)
 a- Avoid unnecessary if conditions (distanceFeed line 195): Instead of checking for isset and an empty string, directly assign the values after applying a coalescing operator (??). 
 b- Use ternary operators: You can use ternary operators to simplify the assignment of values based on conditions.
 c- Improve readability: Use meaningful variable names to improve code readability.

---------------------------------

1- BookingRepository : Again I can follw  several principles, such as simplifying conditional checks, using meaningful variable names, and separating concerns.

 a- I made few changes in store() function and write few private functions to avoid multiple if conditions . 


