# Program-5-a
## Python-Module 5
## EX_NO-05)
### Name: Anish D
### Register Number:212225060017
## AIM:
Add the destructor in the python code
## ALGORITHM:
1. Start the program.
2. Define a class.
3. Define the constructor using **init**() method.
4. Define required methods inside the class.
5. Define a destructor using **del**() method.
6. Create an object of the class.
7. Call the required methods.
8. Delete the object to invoke the destructor.
9. End the program.
## PROGRAM:
```
class Demo:
    def __init__(self):
        print("Alive")
    def __del__(self):
        print("The object no longer exists")
        
obj = Demo()

del obj
```
## OUTPUT:
<img width="601" height="217" alt="image" src="https://github.com/user-attachments/assets/d2c357d1-f297-41ad-89ed-9da896dae821" />

## RESULT:
Thus the Python program demonstrating the use of constructor and destructor has been executed successfully.

# Program-5-b
## Python-Module 5
## EX_NO-05)
### Name: Anish D
### Register Number:212225060017
## AIM:
Write a Python program to Get the name, age and location of a person and display using Multilevel inheritance.
## ALGORITHM:
1. Start the program.
2. Define a base class to store the name.
3. Define a derived class to store the age inheriting from the base class.
4. Define another derived class to store the location inheriting from the previous class (multilevel inheritance).
5. Define methods to set and display the values.
6. Read name, age, and location from the user using input() function.
7. Create an object of the final class.
8. Call methods to set the values.
9. Display the name using the print() function.
10. End the program.
## PROGRAM:
```
class Person:
    def set_name(self, name):
        self.name = name

class Age(Person):
    def set_age(self, age):
        self.age = age

class Location(Age):
    def set_location(self, location):
        self.location = location

    def display(self):
        print(self.name)


name = input()
age = int(input())
location = input()

obj = Location()
obj.set_name(name)
obj.set_age(age)
obj.set_location(location)

obj.display()
```
## OUTPUT:
<img width="570" height="240" alt="image" src="https://github.com/user-attachments/assets/b24b14a0-df3a-4355-88b3-ceb986d1cf64" />

## RESULT:
Thus the Python program to get name, age, and location using multilevel inheritance and display the name has been executed successfully.

# Program-5-c
## Python-Module 5
## EX_NO-05)
### Name: Anish D
### Register Number:212225060017
## AIM:
Write a python program using class to perform addition of three numbers using default constructor
## ALGORITHM:
1. Start the program.
2. Define a class.
3. Define a default constructor using **init**() method.
4. Inside the constructor, read three numbers from the user.
5. Calculate the sum of the three numbers.
6. Display the result using the print() function.
7. Create an object of the class to invoke the constructor.
8. End the program.
## PROGRAM:
```
class sum:
    def __init__(self):
        self.num1=1000
        self.num2=2000
        self.num3=3000
        print(self.num1+self.num2+self.num3)
obj=sum()
```
## OUTPUT:
<img width="435" height="207" alt="image" src="https://github.com/user-attachments/assets/fa849532-408a-41ad-ba6e-e9e4e084c1d5" />

## RESULT:
Thus the Python program using a class with a default constructor to perform addition of three numbers has been executed successfully.

# Program-5-d
## Python-Module 5
## EX_NO-05)
### Name: Anish D
### Register Number:212225060017
## AIM:
Write a Python Program to Display the Student Details
## ALGORITHM:
1. Start the program.
2. Define a class to store student details.
3. Declare variables for student ID and student name.
4. Read student ID and name from the user using the input() function.
5. Convert student ID into integer using int() function.
6. Display the student details using the print() function.
7. Check if student ID is greater than 100000.
8. If true, display "Valid Employee"; otherwise, display "Invalid Employee".
9. End the program.
## PROGRAM:
```
id=int(input())
name=input() 
l=(id,name)
print(l,end="  ")
if(id>100000):
    print("Valid Student")
else:
    print("Invalid Student")
```
## OUTPUT:
<img width="749" height="224" alt="image" src="https://github.com/user-attachments/assets/e7dfea45-d23e-4898-a28b-775aa66e11a3" />

## RESULT:
Thus the Python program to display student details and check whether the employee is valid or not has been executed successfully.

# Program-5-e
## Python-Module 5
## EX_NO-05)
### Name: Anish D
### Register Number:212225060017
## AIM:
write a python program to perform addition and division operation using class and switch case
## ALGORITHM:
1. Start the program.
2. Define a class named saveetha.
3. Define methods add() and div() to perform addition and division.
4. Read two numbers from the user.
5. Create an object of the class.
6. Use a loop to repeatedly read the user’s choice.
7. Use match-case (switch case) to perform:

   * choice 1 → addition
   * choice 2 → division
   * choice 0 → exit
   * otherwise → display "invalid choice"
8. Display the result using the print() function.
9. End the program.
## PROGRAM:
```
class saveetha:
    def add(self, a, b):
        return a + b

    def div(self, a, b):
        return a / b


a = int(input())
b = int(input())

obj = saveetha()

while True:
    choice = int(input())

    match choice:
        case 1:
            print("Result:", obj.add(a, b))
        case 2:
            print("Result:", obj.div(a, b))
        case 0:
            print("Exiting")
            break
        case _:
            print("invalid choice")
```
## OUTPUT:
<img width="485" height="416" alt="image" src="https://github.com/user-attachments/assets/6b72d721-86e9-442e-b20b-46d9ac3462fb" />

## RESULT:
Thus the Python program to perform addition and division using class and switch case has been executed successfully.
