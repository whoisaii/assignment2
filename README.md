 Assignment 2 – Java OOP Project
Repository Description
This repository contains my Java project for Assignment 2. The project is a simple shopping system where there are products and a shopper. The main goal of this work is to show how OOP principles work in practice.

Classes and Objects
Person
* Abstract parent class
* Contains the field name
* Has an abstract method printInfo()
* Used to show abstraction
Shopper
* Child class that extends Person
* Represents a customer
* Overrides the printInfo() method
* Used to show inheritance and polymorphism
Product
* Represents a product with name and price
* All fields are private
* Getters and setters are used
* Overrides toString(), equals() and hashCode()
* Used to show encapsulation
Main
* Creates objects of Product and Shopper
* Stores products in an ArrayList
* Implements searching, filtering and sorting
* Runs and tests the program

* 
OOP Concepts Used:
* Encapsulation
All fields are private, and I use getters and setters to work with them.
This protects the data and does not allow direct access to fields.
* Abstraction
I used an abstract class called Person.
It contains common data and methods for child classes.
* Inheritance
The Shopper class extends the Person class.
This means it inherits fields and methods from the parent class.
* Polymorphism
The printInfo() method is overridden in the Shopper class.
The same method works differently in the child class.
* Data Pool
Products are stored in an ArrayList.
This allows working with many objects at the same time.
* Searching
Products can be found by their name.
* Filtering
Products can be filtered by price.
* Sorting
Products are sorted by price using Comparator.
* Method Overriding
The methods toString(), equals() and hashCode() are overridden.I overrode these methods to print objects correctly and compare them properly.

Conclusion
In this project I used the main object-oriented programming principles in Java.
I worked with abstraction, inheritance and polymorphism and showed how they can work together in one program.
Also, I used collections like ArrayList to store and manage data, which makes the program more organized and easier to work with.
Overall, this project helped me better understand how OOP concepts are used in real Java programs.
