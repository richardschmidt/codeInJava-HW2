# MIS4310 – Programming in Java
# Homework 2

Problem 1 (20 points):

The sales department of a company has gathered monthly sales numbers (number of sold items and the sales revenue in dollars) of each product they have been selling for many years. The new director of the department wants to know how long (how many months) it has taken the department to achieve the first million dollars of sales of each product that it has sold. The department provides a software analyst with the sales data and asks him/her to write a Java program that can provide the information that the director needs (by printing out the information to the console). 

For each product, the program should read the monthly sales data from the console and print out the desired information in months. The program should check to be sure that values of monthly sales are not negative.

Important Notes:
•	The program can be used for only one product at any time when it runs.
•	For the purpose of testing, students can make up the data of monthly sales of some imaginary product.

Important Notes:
•	In Eclipse IDE, inside the newly created project HOMEWORK_2, students should create a new program, i.e. a class, named: Program_1 under a new package named PROBLEM_1for his/her work on this problem.
•	To submit, students copy all the code of the program into a Notepad file (and keep all the original Eclipse format) – NOT Microsoft Words, name the file as “hw2_Program1” (the file should have the suffix .txt), and submit it via E-Learning (attach the file)


Problem 2 (20 points):

The consumer loan department of a bank asks a software analyst to write a Java program that can calculate the following amounts of a loan:
•	the monthly payment of a mortgage
•	the total payment (after all the monthly payments have been made)
•	the total interest (after all the monthly payments have been made)

After reading (from the console) necessary data – the loan amount, the loan period (in months), and the annual interest rate, the program processes the data and prints out (to the console) the following pieces of information in only one line:
•	The loan amount
•	The loan period (how many months)
•	The annual interest rate

Then the program prints out the monthly payment in the next line, and prints out the following pieces of information in another line:
•	The monthly payment
•	The total payment 
•	The total interest 

The inputs must be verified to be sure that they are not negative. All the floating-point numbers of the outputs have 2 digits after the floating point.

Important Notes:
•	Annual interest rate is entered as percentage, i.e. 4.25 is entered for 4.25%

•	Formula to compute the monthly payment:

 

•	Formula to compute the monthly interest rate (in this formula, interest rate has it real value, not %. To get real value, divide the input of interest rate by 100)
Monthly interest rate = annual interest rate / 12

•	Formula to compute the total payment
Total payment = monthly payment * number of months

•	Formula to compute the total interest
Total interest = total payment - original loan amount


Important Notes:
•	In Eclipse IDE, inside the newly created project HOMEWORK_2, students should create a new program, i.e. a class, named: Program_2 under a new package named PROBLEM_2 for his/her work on this problem.
•	To submit, students copy all the code of the program into a Notepad file (and keep all the original Eclipse format) – NOT Microsoft Words, name the file as “hw2_Program2” (the file should have the suffix .txt), and submit it via E-Learning (attach the file)








Problem 3 (20 points):

The consumer loan department of a bank asks a software analyst to write a Java program that can calculate
•	the monthly payment of a mortgage
•	the principal paid in each monthly payment
•	the interest paid in each monthly payment, 

After reading (from the console) necessary data – the loan amount, the loan period (in months), and the annual interest rate, the program processes the data and then prints out (to the console) the following pieces of information as follows:
•	The loan amount in the 1st line
•	The loan period (how many months) in the 2nd line
•	The annual interest rate in the 3rd line
(Leave the next line blank)


Next, the program prints out the following text as shown:

Payment #:		Monthly Payment		Principal	Interest	Balance

Andfinally the program prints out the following details of a monthly payment (one line for each payment)
•	Payment #
•	Monthly payment amount
•	Principal paid in the monthly payment
•	Interest paid in the monthly payment
•	Balance of the loan after the monthly payment

The inputs must be verified to be sure that they are not negative. All the floating-point numbers of the outputs have 2 digits after the floating point.

Sample of the outputs:

Loan amount: 10000.00 
Number of months:        6 
Annual interest rate:     2.00 

Payment # 	 Monthly Payment 	 Principal 	 Interest 	 Balance

1 		 1676.40 		 1659.74 	 16.67 		 8340.26
2 		 1676.40 		 1662.50 	 13.90 		 6677.76
3 		 1676.40 		 1665.27 	 11.13 		 5012.49
4 		 1676.40 		 1668.05 	 8.35 		 3344.44
5 		 1676.40 		 1670.83 	 5.57 		 1673.61
6 		 1676.40 		 1673.61 	 2.79 		   0.00



Important Notes:
•	Formula to compute the monthly payment:

 

•	Other formulas:
o	Monthly interest rate = annual interest rate / 12
o	Interest (in monthly payment) = monthly interest rate * current balance
o	principal (in monthly payment) = monthly payment - interest
o	balance (after monthly payment has been paid) = current balance - principal


Important Notes:
•	In Eclipse IDE, inside the newly created project HOMEWORK_2, students should create a new program, i.e. a class, named: Program_3 under a new package named PROBLEM_3 for his/her work on this problem.
•	To submit, students copy all the code of the program into a Notepad file (and keep all the original Eclipse format) – NOT Microsoft Words, name the file as “hw2_Program3” (the file should have the suffix .txt), and submit it via E-Learning (attach the file)



		
Problem 4 (20 points):

Write a Java program that reads the full name and GPA of a group of 5 students from the console and stores the data – full names and GPA’s – in single-dimensional arrays. The program should check to be sure that each input of student name is not empty string and GPA is not negative.

After processing the data, the program prints out (to the console) the following pieces of information, each in one line:
•	The average GPA of this group of students .
•	Full name and GPA of the student(s) that has(have) the highest GPA
o	Notes: If more than one student have the highest GPA, print out them all – one student and his/her GPA in one line.
•	Full name and GPA of the student(s) that has(have) the lowest GPA
o	Notes: If more than one student have the lowest GPA, print out them all – one student and his/her GPA in one line.

All the floating-point numeric output values should have 2 digits after the floating point.


Important Notes:
•	In Eclipse IDE, inside the newly created project HOMEWORK_2, students should create a new program, i.e. a class, named: Program_4 under a new package named PROBLEM_4 for his/her work on this problem.
•	To submit, students copy all the code of the program into a Notepad file (and keep all the original Eclipse format) – NOT Microsoft Words, name the file as “hw2_Program4” (the file should have the suffix .txt), and submit it via E-Learning (attach the file)




Problem 5 (20 points):

Imagine that two baseball teams, Rangers and Yankees, play in the World Series Championship games this year. They will play 7 games. Write a Java program that can store the imagined scores (home runs) of each team at the end of the first official nine innings of each game of the all 7 games. The program reads the scores of each team from the console and stored them in arrays. At the end, the program displays (to the console) the result of each game (for all 7 games), i.e. which team is winning or the teams tie at the end of the 9th inning.

Sample of the output:
Game 1:  Rangers wins
Game 2: Yankees wins.
Game 3: Both the teams tied at the end of the 9th inning.
…
Game 7: Rangers wins.

Important Notes:
•	In Eclipse IDE, inside the newly created project HOMEWORK_2, students should create a new program, i.e. a class, named: Program_5 under a new package named PROBLEM_5 for his/her work on this problem.
•	To submit, students copy all the code of the program into a Notepad file (and keep all the original Eclipse format) – NOT Microsoft Words, name the file as “hw2_Program5” (the file should have the suffix .txt), and submit it via E-Learning (attach the file)