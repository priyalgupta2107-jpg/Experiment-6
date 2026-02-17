# Aim: Study of Conditional Statements in Python
# Theory:
- Conditional statements are used to make decisions in a Python program.  
- The input() function is used to accept data from the user.  
- The split() function is used to separate the input into multiple values.  
- The map() and int() functions are used to convert input values into integers.  
- Variables are used to store and process input data.  
- The if, elif, and else statements are used to check different conditions.  
- Relational operators such as ==, >, <, >=, and <= are used for comparison.
- Logical operators such as and, or, and not are used to combine multiple conditions in decision making.  
## Algorithm – Q1: Check whether a number is positive, negative, or zero
1.Start.  
2.Input a number number.  
3.If num > 0, print "Number is positive".  
4.Else if num < 0, print "Number is negative".   
5.Else print "Number is zero".  
6.Stop.  
## Algorithm – Q2: Check whether a number is even or odd
1.Start.  
2.Input a number number.  
3.If num % 2 == 0, print "Number is even".    
4.Else print "Number is odd".  
5.Stop.  
## Algorithm – Q3: Find the largest of three numbers
1.Start.  
2.Input three numbers a, b, and c.  
3.If a >= b and a >= c, then a is largest.  
4.Else if b >= a and b >= c, then b is largest.  
5.Else c is largest.  
6.Display the largest number.  
7.Stop.  
## Algorithm – Q4: Calculate grade based on marks
1.Start.  
2.Input marks.  
3.If marks ≥ 90 → Grade A.  
4.Else if marks ≥ 75 → Grade B.  
5.Else if marks ≥ 60 → Grade C.  
6.Else if marks ≥ 40 → Grade D.  
7.Else → Fail.  
8.Display grade. 
## Algorithm – Q5: Check whether a year is a leap year
1.Start.  
2.Input year.  
3.If (year divisible by 4 AND not divisible by 100) OR (year divisible by 400) then print "Leap year".  
4..Else print "Not a leap year".   
5.Stop.  
## Algorithm – Q6: Calculate gross salary
1.Start.  
2.Input basic salary.  
3.If basic ≤ 10,000.  
4.Calculate HRA = 20% of basic and DA = 80% of basic.  
5.Else if basic ≤ 20,000.  
6.Calculate HRA = 25% of basic and DA = 90% of basic.  
7.Else Calculate HRA = 30% of basic and DA = 95% of basic.  
8.Calculate Gross Salary = Basic + HRA + DA.  
9.Display gross salary.  
10.Stop.   
## Algorithm – Q7: Calculate income tax
1.Start.  
2.Input annual income.  
3.If income ≤ 2,50,000 → set tax = 0.  
4.Else if income ≤ 5,00,000 → tax = (income − 2,50,000) × 5%.  
5.Else if income ≤ 10,00,000 → tax = (2,50,000 × 5%) + (income − 5,00,000) × 20%.  
6.Else → tax = (2,50,000 × 5%) + (5,00,000 × 20%) + (income − 10,00,000) × 30%.  
7.Display calculated tax.  
8.Stop.  
## Algorithm – Q8: Check whether a character is vowel or consonant
1.Start.  
2.Input a character ch.  
3.If ch is in (a, e, i, o, u, A, E, I, O, U) print "Vowel".  
4..Else print "Consonant".  
5.Stop.  
## Algorithm – Q9: Increment date
1.Start.  
2.Input date in dd/mm/yyyy format.  
3.Separate the date into day, month, and year.  
4.Determine maximum days in the month (31 for 1,3,5,7,8,10,12; 30 for 4,6,9,11; 28/29 for February using leap year).  
5.If day < maximum days, increment day by 1.  
6.Else set day = 1.  
7.If month = 12, set month = 1 and increment year.  
8.Else increment month by 1.  
9.Display the new date and Stop.  
# Conclusion: 
Python conditional statements help in making decisions by executing code based on given conditions.
