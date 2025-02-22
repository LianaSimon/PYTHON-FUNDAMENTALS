# PYTHON-FUNDAMENTALS

(Assg:1 on Python-Used Jupyter Notebook to execute the codes)

## Exercise 1

### * Write Python code that prints your name, student number and email address.


#### SCRIPT

print=input("Enter your name:")

print=int(input("Enter your student number:"))

print=input("Enter your email address")


OR

print("The name of the student is Liana Simon")

print("The student number is 047")

print("The student email address is liana@gmail.com")


![image](https://github.com/user-attachments/assets/942fc848-2253-4cd0-85b2-a69918f2d4af)


## Exercise 2

### * Write Python code that prints your name, student number and email address using escape sequences.     


#### SCRIPT

print("The name of the student is:\n ")

print("Liana Simon")

print("\n")

print("The student number is\t",":",0,"\\",47)

print("\n")

print("The email address of the student is:\tliana@gmail.com")


![image](https://github.com/user-attachments/assets/5a203b62-92ec-4206-b6e0-c6bad3638aec)



## Exercise 3


### * Write Python code that add, subtract, multiply and divide the two numbers. You can use the two numbers 14 and 7    


#### SCRIPT     

a=14

b=7 

print(a+b) #addition

print(a-b) #subtraction

print(a*b) #multiplication

print(a/b) #division


![image](https://github.com/user-attachments/assets/9996cb44-038b-411d-98aa-2ff77940c3c2)


### OR

a=14

b=7

print("The addition of",a,"and",b,"gives:",a+b) #addition

print("The subtraction of",a,"and",b,"gives:",a-b) #subtraction

print("The multiplication of",a,"and",b,"gives:",a*b) #multiplication

print("The division of",a,"and",b,"gives:",a/b) #division


![image](https://github.com/user-attachments/assets/7b82ca97-fa40-4fc4-b3a3-b11552fe8161)


## Exercise 4


### * Write Python code that displays the numbers from 1 to 5 as steps. 


#### SCRIPT  

for i in range(1,6):

    print(i)


![image](https://github.com/user-attachments/assets/18c6e29a-a723-44b7-92ae-494ab90b0e40)



## Exercise 5


### * Write Python code that outputs the following sentence (including the quotation marks and line break) to the screen: 
###   An example runs of the program:  
###   "SDK" stands for "Software Development Kit", whereas 
###   "IDE" stands for "Integrated Development Environment". 
 

#### SCRIPT 

print("\"SDK\" stands for \"Software Development Kit\",whereas")

print("\n")

print("\"IDE\" stands for \"Integrated Development Environment.\"")

![image](https://github.com/user-attachments/assets/b859f15e-5f99-45ff-bc09-2eea56c22358)


## Exercise 6

### * Practice and check the output

print("python is an \"awesome\" language.")

print("python\n\t2023")

print('I\'m from Entri.\b')

print("\65")

print("\x65")

print("Entri", "2023", sep="\n")

print("Entri", "2023", sep="\b")

print("Entri", "2023", sep="*", end="\b\b\b\b")
 

#### OUTPUT 


![image](https://github.com/user-attachments/assets/3c7b0deb-cce1-4d38-8b6c-dcc249eaf9c7)


## Exercise 7

### * Define the variables below. Print the types of each variable. What is the sum of your variables? (Hint: use a type conversion function.) What datatype is the sum?
###   num=23
###   textnum="57"
###   decimal=98.3

## SCRIPT

num=23

textnum="57"

decimal=98.3

print(type(num))

print(type(textnum))

print(type(decimal))

sum=num+int(textnum)+decimal

print("Sum of the variables=",sum)

print("The type of SUM is ",type(sum))


![image](https://github.com/user-attachments/assets/c6923bd4-5d2d-4211-87f5-dd6fa65611c7)


## Exercise 8

### * Calculate the number of minutes in a year using variables for each unit of time. print a statement that describes what your code does also. 
###   Create three variables to store no of days in a year, minute in a hour, hours in a day, then calculate the total minutes in a year and print the values
### (hint) total number of minutes in an year =No.of days in an year * Hours in a day * Minutes in an hour


## SCRIPT

days=365

minutes=60

hours=24

totalmins=days*hours*minutes

print("The total number of minutes can be found by multiplying-no of days in a year, minute in a hour and hours in a day")

print("The total number of minutes in a year=",totalmins)


![image](https://github.com/user-attachments/assets/e2d4fa56-e6ee-482d-b3fe-ad7b02b5457f)



## Exercise 9

### Write Python code that asks the user to enter his/her name and then output/prints his/her name with a greeting


## SCRIPT

a=input("Please enter your name:")

print("Hi",a,", welcome to Python programming:)")

![image](https://github.com/user-attachments/assets/83d2825b-7e37-4c8c-923f-d1f4b543795f)


## Exercise 10

### Name your file: PoundsToDollars.py
### Write a program that asks the user to enter an amount in pounds (£) and the program calculates and converts an amount in dollar ($)
### An example runs of the program:
### Please enter amount in pounds: XXX
### £ XXX are $ XXX

## SCRIPT

pounds=float(input("Enter the amount in pounds(£)"))

dollars=pounds*1.26 # Exchange rate is 1pound=1.26 dollars

print("£",pounds,"are","$",dollars)


![image](https://github.com/user-attachments/assets/0025243f-a66d-405c-8faf-6eb46e752e78)











