47. If I was to enter the value of insertMoney() as 0, I will get a message telling me to input a value higher than zero, since that's what's written in the body of the method. By checking in BlueJ, I was able to confirm my hypothesis.

48. I think that if we were to use the greater-or-equal-to operator, then we can successfully input the amount of 0 without getting a message telling us that we can't. After testing it out, I was proven to be right.

50. The feature that we used the boolean to control was the isVisible;, which controls whether or not the circle object is currently visible on the canvas. I think it's a pretty good choice since a boolean basically represents a two-state condition.

51. We can see that the Better Ticket Machine's printTicket uses a conditional (if, else), which prints a message when you try to print a ticket without having enough money. Additionally, the Better Ticket Machine has a line which subtracts the price from the balance of the machine every time we print a ticket (and also aline that checks whether we have enough balance to print a ticket), compared to the Naive Ticket Machine's returning the balance to 0 every time we print a ticket. 

52. Yes, it is possible, and the code will still compile just like normal. However, the main purpose of the else in this method is to prevent the error message from being printed when the ticket printing succeeds. By removing it, the error message will always be printed after we print the ticket. If we don't insert enough money, then the message will of course be printed.

53. No, it is not possible for the balance to be set to a negative number after printing a ticket because this line: if(balance >= price) prevents that possibility from happening. The balance must always have enough cents to cover the ticket cost before it does the substraction, or a message of how much money you still need to insert will be printed.

54. + addition, - subtraction, * multiplication, / division, % modulus

55. saving = price * discount;

56. mean = total / count;

59. This version of refundBalance() doesn't give the same result as the original because it's from the naive machine (which means that it's broken). In this version, the balance always gets returned back to 0 (balance = 0;) before returning the balance, which means that we will never get a refund since all the money simply went poof!

60. From what I've learned, the return statement immediately exits the method that it's in, which means in this case that it won't be able to run anything after the line with the return statement. So, the balance line will have an error message of "unreachable statement", because it literally is unreachable. It cannot be run.

61. Yes, this new version can be compiled, but I think the behavior of the method isn't right. The (int price = cost;) basically creates a new local variable, so everything the actual field doesn't get the value that we set. Testing it out confirms that everything is now 0. The printed ticket is 0 cents because that's the default value.
