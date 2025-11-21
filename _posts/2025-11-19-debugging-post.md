My other part of ranting about: Debugging in python.

<img src="/blog/images/debug.png" alt="debug"

So as I am coding in python, I noticed there is a very different tool that doesn't really fit apart of the whole python3 thing to me. That is what I call: Debugging. Basically to summerize it up, Debugging is a tool in python where it shows the users steps on what the output is doing, like going through conditionals, statements, and even errors. At first, Debugging looks useless to some people who just started using python, but it actually could help you on something that you have done wrong step by step. Here are four examples of how i used debugging process to solve logical problems.

--------------------------------------------------------------------------------

EXAMPLE 1: Counting how many spaces there are in a sentence.

<img src="/blog/images/debug1.png" alt="debug1">

In this picture, You can see a code that has a sentence. The user wants to know how many spaces there are. When running the output, the total spaces given doesn't tell us how many they are. Mistakenly, it gave the user zero spaces. Once debugging the output to see if there is any changes, it processes each character through the letters, especially spaces too. If you have keen eyes, you would notice that as the output is processing each character, you realize that the if conditional statement is not working when it looks at a space character. If you want to fix that, you'd have to add a space character inside the if statement where it reads: If char == "". Just simply add a space inside the quotation marks and you would be good to try it again, which registers the spaces and counts by 1. Now it tells you how many spaces there are in the following sentence.

