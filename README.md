# Sukhman Coding

* This File is to understand how i made uygfytf.py file.

* I selected topic of "python program to check if number is even or odd."

# Start

* First i created variable caled "num" and i used int(input()) function to input numbers.

* I put "Enter a number: " in input() function so the user can understand that you have to enter numbers.

num = int(input("Enter a number: "))

* I used "if" and "else" statements to check if number is even or odd.

* I used "if" for if number can be divided by 2. If not, i used "else" statement.

* I used print() function to print "{0} is Even".format(num)) if number is divided by 2 in "if" statement. If not, i also used print() function to print "{0} is odd".format(num)) if number is not devided by 2 in "else" statement.

if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))
   
 * The code will look like:
  
  num = int(input("Enter a number: "))
  
if (num % 2) == 0:

   print("{0} is Even".format(num))
else:

   print("{0} is Odd".format(num))
