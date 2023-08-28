## Day 2: Data Types BMI Calculator, Life in Weeks and the Tip Calculator.

Welcome to Day 2 of the 100 days of Code. The Complete Python Pro Bootcamp for 2023! On this day we will be exploring different data types, and working on projects such as BMI Calculator, Life in Weeks and The Tip Calculator.

## Learning Objectives
- Understand different data types in Python.
- Apply Python programming concepts to solve practical problems.
- Develop projects to enhance your coding skills and understanding.

## Concepts Covered
1.Dta Types in Python.
2.Using Mathematical Operations.
3.Implementing project-based exercises
4.Enhancing problem-solving skills.

## Exercise 1:Data Types
Python provides several built-in data types such as integers,floats,strings,lists, and booleans.Understanding and working with these data types are crucial in programming.

```python
#Example 1: Integer data type
age = 25

#Example 2:Float data type
height = 1.75

#Example 3:String data type
name = "Ruperth"

#Example 4:List data type
grades = [70,80,90,85]

#Example 5:Boolean data type
is_student = True
```
## Exercise 2: BMI Calculator
The Body Mass Index (BMI) Calculator is a useful tool for determining whether an individual has a healthy body weight. We develop a simple BMI Calculator using Python.

```python
# Example 1: Calculating BMI
weight = 70
height = 1.75

bmi = weight / height ** 2
print("Your BMI is:", bmi)

# Output
# Your BMI is:22.86
```

## Exercise 3:Life in Weeks
Understanding the limited time we have in our lives can help us make most of it. The Life in Weeks peoject will calculate how many weeks and average person has left to live based on their current age.

```python
# Example 1: Calcualting weeks left to live
age = 22
remaining_years = 90 - age
remaining_months = remaining_years * 12
remaining_weeks = remaining_months * 4 

print("You have approximately",remaining_weeks, "weeks to live.")

#Output:
# You have approximately 2228 weeks left to live.
```

## Exercise 4: Project: Tip Calculator
The Tip Calculator Project provides a practical example of how programming can help in everyday situations. We will develop a program to calculate the total bill amount including the tip, given the bill amount and the desired tip percentage.

```python
# Example 1:Calculating total bill amount with tip
bill_amount = float(input("Enter the bill amount: Ksh"))
tip_percentage = float(input("Enter the desired tip percentage:"))

tip_amount = bill_amount *
(tip_percentage / 100)
total_amount = bill_amount + tip_amount

print("The tip amount is: Ksh", round(tip_amount,2))
print("The total bill amount is: Ksh", round(total_amount,2))
```