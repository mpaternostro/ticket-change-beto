# ticket-change-beto

The new "Avengers" movie has just been released! There are a lot of people at the cinema box office standing in a huge line. Each of them has a single 100, 50 or 25 dollar bill. An "Avengers" ticket costs 25 dollars.

Beto is currently working as a clerk. He wants to sell a ticket to every single person in this line.

Can Beto sell a ticket to every person and give change if he initially has no money and sells the tickets strictly in the order people queue?

Step #1
Create a function that returns YES, if Beto can sell a ticket to every person and give change with the bills he has at hand at that moment. Otherwise return NO.

Examples:
tickets([25, 25, 50]) // => YES
tickets([25, 100]) // => NO. Beto will not have enough money to give change to 100 dollars
tickets([25, 25, 50, 50, 100]) // => NO. Beto will not have the right bills to give 75 dollars of change (you can't make two bills of 25 from one of 50)
