CSC310 - PROJECT 1

--------------------------------------------
PROJECT - RADIXSORT
File: CSC310Project1Radix.java
--------------------------------------------
Summary:
This program will sort any amount of numbers that it is fed using the
Radix Sort method. The program will sort numbers in a queue, digit by
digit, placing the numbers into buckets and then placing the numbers
back into the queue. The program will allow the user to enter the amount
of numbers they wish to sort. Then the program will let the user enter
each number in the queue, one by one. The program will sort the numbers
then print out the sorted queue to the user.

--------------------------------------------
Program Used:
The language used was Java. The program it was written in was Netbeans
IDE 8.2. Java is required for Netbeans to run, you can find a
download to both Java and Netbeans at the following address:
https://netbeans.org/downloads/
By installing these programs an opening up the java program file within
Netbeans, the user will have full access to the program, its comments,
and a means to run the program.

--------------------------------------------
Testing:
Upon running the program, the program will prompt the user to enter the
amount of numbers to sort:

"This program will apply a Radix sort to a list of numbers 
Please enter how many numbers you would like to sort:"

At that point, the user is free to enter the amount of numbers they would
like to sort. The user can submit that number to the program by pressing
enter when done.

After submitting the amount, the program will prompt the user to enter
a number:

"Enter a number:"

The user can put in any integer to the program. To submit the number, the
user must press enter.

The program will then repeat the process of asking the user to enter a
number. This will run [x] amount of times. X being the amount of numbers
the user first stated they would like to sort.

Once you have entered all [x] numbers, the progrma will then display
the list of numbers you have entered, all sorted:

"The sorted list is: "

Then followed by the sorted list.

--------------------------------------------
Examples:

run:
This program will apply a Radix sort to a list of numbers 
Please enter how many numbers you would like to sort: 5
Enter a number: 22
Enter a number: 44
Enter a number: 99
Enter a number: 22
Enter a number: 771

The sorted list is: 
22 22 44 99 771 

--------------------------------------------
run:
This program will apply a Radix sort to a list of numbers 
Please enter how many numbers you would like to sort: 3
Enter a number: 14
Enter a number: 0
Enter a number: 99

The sorted list is: 
0 14 99

--------------------------------------------

CSC310 - PROJECT 1

--------------------------------------------
PROJECT - POSTFIX EXPRESSION EVALUATION
File: CSC310Project1.java
--------------------------------------------
Summary:
This program will take any expression that is previously written in
postfix form and evaluate that expression then return the result
to the user. The program will take the expression that is entered and 
go through each character in the string. The program will then determine
if the character is a number or an operator. Then the program will
perform the given operations on the given numbers.

--------------------------------------------
Program Used:
The language used was Java. The program it was written in was Netbeans
IDE 8.2. Java is required for Netbeans to run, you can find a
download to both Java and Netbeans at the following address:
https://netbeans.org/downloads/
By installing these programs an opening up the java program file within
Netbeans, the user will have full access to the program, its comments,
and a means to run the program.

--------------------------------------------
Testing:
Upon running the program, the program will prompt the user to enter an
expression given in postfix form:

"Input an expression in post fix form, using onlynumbers, spaces and
'+','-','*','/' :"

At that point, the user is free to enter an expression in postfix form

After submitting the expression, the program will evaluate the
expression and return the result back to the user:

"((the expression)) will evaluate to: ((result))"

with ((the expression)) being the original expression entered and
((result)) being the result.

--------------------------------------------
Examples:

run:
Input an expression in post fix form, using onlynumbers, spaces and '+','-','*','/' : 
52+83-*4/

(52+83-*4/) will evaluate to: 8