47. If I was to enter the value of insertMoney() as 0, I will get a message telling me to input a value higher than zero, since that's what's written in the body of the method. By checking in BlueJ, I was able to confirm my hypothesis.

48. I think that if we were to use the greater-or-equal-to operator, then we can successfully input the amount of 0 without getting a message telling us that we can't. After testing it out, I was proven to be right.

52. Yes, it is possible, and the code will still compile just like normal. However, the main purpose of the else in this method is to prevent the error message from being printed when the ticket printing succeeds. By removing it, the error message will always be printed after we print the ticket. If we don't insert enough money, then the message will of course be printed.

53. No, it is not possible for the balance to be set to a negative number after printing a ticket because this line: if(balance >= price) prevents that possibility from happening. The balance must always have enough cents to cover the ticket cost before it does the substraction, or a message of how much money you still need to insert will be printed.

54. 

55. saving = price * discount;

56. mean = total / count;
