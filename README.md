# python-adding-numbers

In this program, we asked the user to enter two numbers and this program displays the sum of two numbers entered by user.

We use the built-in function input() to take the input. Since, input() returns a string, we convert the string into number using the float() function. Then, the numbers are added.

Alternative to this, we can perform this addition in a single statement without using any variables as follows.

print('The sum is %.1f' %(float(input('Enter first number: ')) + float(input('Enter second number: '))))
