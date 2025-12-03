My other part of ranting about: Debugging in python.

<img src="/blog/images/debug.png" alt="debug">

So as I am coding in python, I noticed there is a very different tool that doesn't really fit apart of the whole python3 thing to me. That is what I call: Debugging. Basically to summerize it up, Debugging is a tool in python where it shows the users steps on what the output is doing, like going through conditionals, statements, and even errors. At first, Debugging looks useless to some people who just started using python, but it actually could help you on something that you have done wrong step by step. Here are four examples of how i used debugging process to solve logical problems.

--------------------------------------------------------------------------------

EXAMPLE 1: Counting how many spaces there are in a sentence.

<img src="/blog/images/debug1.png" alt="debug1">

In this picture, You can see a code that has a sentence. The user wants to know how many spaces there are. When running the output, the total spaces given doesn't tell us how many they are. Mistakenly, it gave the user zero spaces. Once debugging the output to see if there is any changes, it processes each character through the letters, especially spaces too. If you have keen eyes, you would notice that as the output is processing each character, you realize that the if conditional statement is not working when it looks at a space character. 

If you want to fix that, you'd have to add a space character inside the if statement where it reads: If char == "". Just simply add a space inside the quotation marks and you would be good to try it again, which registers the spaces and counts by 1. Now it tells you how many spaces there are in the following sentence. With keen eyes, you will be able to understand in no time.

<img src="/blog/images/solution1.png" alt="debug">

--------------------------------------------------------------------------------

EXAMPLE 2: Determine if numbers 1 to n are even or odd.

<img src="/blog/images/debug2.png" alt="debug2">

In the next example, you see a simple code where it tells you to give it a number and tells you which nuber is even or odd based on the range of what you put. Once printed, the first thing you would notice is that there is an error. Well, pretty simple if you have basic knowledge by making that input into an integer. I ran the code afterwards and gave in the number just to realize that all even numbers are considered to be odd. I find this very weird so I debugged the code and realized that all of the even numbers are joining in the odd session.

To fix this solution, Just change the greater than symbol to an equal to (==). Pretty tricky considering that there is just one error just like the other one where you have to look very closely. Once I debugged the code, the even numbers are now going to their right places instead of them being odd.

<img src="/blog/images/solution2.png" alt="debug2">

--------------------------------------------------------------------------------

EXAMPLE 3: Calculate the factorial of a given number.

<img src="/blog/images/debug3.png" alt="debug3">

For the third example, you got a given code which tells you a factorial of a number. If you do not know what is a factorial, in quick summery, its basically a product of numbers less than to the following equal number. Using that knowledge, I run the code and put 5 as my input. The code makes a small error because the print area uses the plus symbol instead of a coma. Fixed that and the code ran perfectly fine, until I realized that the factorial of 5 is NOT 24. I debugged the code and found the issue inside.

The error in this code is inside the for loop, where the number is not being added at all which completely forget to multiply again. To fix that, all you need to do instead of using the coma thats between the 1 and the num, replace it with the plus symbol so it adds the given factorial of the number correctly. I debugged the code making sure it adds the given number by 1, in which case it does.

--------------------------------------------------------------------------------

EXAMPLE 4: Ask user to enter the correct password but only give them 3 attempts

<img src="/blog/images/debug4.png" alt="debug4">

Here is the last example of my use of debugging. This given code is about entering a password, but there is a LOT of errors that are evidently shown. the very first one being the correct password being the string of "incorrect_password". I debugged the code to see what is the problem is when i typed the "secret" password.

<img src="/blog/images/solution4.png" alt="debug4">

The issue of that is the correct password is incorrect, because "secret" does not equal to "incorrect_password". I changed that "incorrect_password" string into being the variable called correct_password, which the string itself is "secret".

Another problem coming from the first one is the code asking me to enter the password even if i put the correct password. As I keep on debugging the code, the output seems to loop again. Once you get something right, the output should completely stop.

<img src="/blog/images/solution44.png" alt="debug4">
<img src="/blog/images/solution44444.png" alt="debug4">

I added a break inside the if statement so the code stops once I get the code correct. I ran the code completely again with the two errors that I have fixed and it worked as expected. But there is one more error that even I didn't have the sharpest eyes to notice what was it.


The last error in the following code is the attempt count. When I debugged the code, I purposely gave three incorrect answers. The code should completely be stopped, but it gave me a 4th attempt to enter the password.

<img src="/blog/images/solution444.png" alt="debug4">

I put a wrong code one more time and it completely stopped. inside the "if attempts" statement, change that greater than symbol to a equal to symbol. When you get the code wrong three times, the variable, "attempts" would equal to three, and the statement does not say that three is greater than three itself. When changed as an equal to, it will now work properly and completely shut down once putting the incorrect password three times.

<img src="/blog/images/solution44444.png" alt="debug4">

--------------------------------------------------------------------------------

Well that was all my shown examples of how debugging can be annoying, but somewhat helpful for those who have keen eyes. Im very surprised debugging made me understand how the code is logically being errored instead of directly giving me a result of something that I get completely mad at. 