# Object-Oriented Programming (OOP) in python

**Here my sloving the oop questions.**

1. **Create a Class**:
   - Write a class Mobile with attributes brand and price.
   - Create two objects of the class and display their attributes using a method.

**code:**
```python
class mobile:
    def __init__(self, brand , prices):
        self. brand  = brand
        self. prices = prices

    def display(self):
        print (f"{self.brand} is for sale!")
    
    def rate(self):
        print (f"{self.prices} is the prices of this  {self.brand} mobile")
        


mobile1 = mobile("iphone" , 500000)
mobile2 = mobile("oppo" , 600000)

mobile1.display()
mobile2.display()

mobile1.rate()
mobile2.rate()
```
**output**
```python
iphone is for sale!
oppo is for sale!
500000 is the prices of this  iphone mobile
600000 is the prices of this  oppo mobile
```
2. **Method Definition**:
   - Define a class Student with attributes name and marks.
   - Write a method display_info() that prints the student's name and marks.
   - Create multiple objects of the Student class and call the method on each.

**code:**
```python
class student:
    def __init__(self, name, marks):
        self.name = name
        self.marks = marks
    def display_info(self):
        print(f"{self.name}, {self.marks}")

student1 = student("sandhya",350)
student2 = student("gangothri",450)
student3 = student("tani",250)
student4 = student("manaswin",550)
student5 = student("shashikala",450)
student6 = student("manu",550)
student7 = student("gowda",440)
student8 = student("devaraj",400)
student9 = student("sudha",435)
student10 = student("shivashakthi",550)

student1.display_info()
student2.display_info()
student3.display_info()
student4.display_info() 
student5.display_info() 
student6.display_info() 
student7.display_info() 
student8.display_info() 
student9.display_info() 
student10.display_info()
```
**output**
```python
sandhya, 350
gangothri, 450
tani, 250
manaswin, 550
shashikala, 450
manu, 550
gowda, 440
devaraj, 400
sudha, 435
shivashakthi, 550
```
4. **Create a Class with a Constructor**:
   - Write a class Movie with attributes title and rating using the __init__() constructor.
   - Define a method to display the movie’s title and rating.
   - using the default Parameters (default rating)

**code:**
```python
class Movie:
    def __init__(self, title, rating=5.4):
        self.title = title
        self.rating = rating

    def display_info(self):
        print(f"{self.title}, {self.rating}")

movie1_title = input("Enter the title of the first movie: ")
movie2_title = input("Enter the title of the second movie: ")
movie3_title = input("Enter the title of the third movie: ")
movie4_title = input("Enter the title of the fourth movie: ")

movie1 = Movie(movie1_title)
movie2 = Movie(movie2_title, 5.5)
movie3 = Movie(movie3_title, 8.5)
movie4 = Movie(movie4_title,10)

movie1.display_info()
movie2.display_info()
movie3.display_info()
movie4.display_info()
```
**output**
```python
Enter the title of the first movie:  APPU
Enter the title of the second movie:  MR & MRS. RAMACHARI
Enter the title of the third movie:  KGF-1
Enter the title of the fourth movie:  KGF-2
APPU, 5.4
MR & MRS. RAMACHARI, 5.5
KGF-1, 9.5
KGF-2, 10
```
 

