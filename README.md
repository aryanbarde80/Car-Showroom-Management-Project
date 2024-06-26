﻿# Car-Showroom-Management-System-Project

--------------------------------------------------
Project made with Java with OOPS…
--------------------------------------------------


This project is based on two important pillars of object oriented programming which are Inheritance and Polymorphism.

It contains mainly two things which are classes and interface. We have three classes which are namely Showroom, Employees and Cars. The interface that we used here is Utility.

This project does not have any database connectivity, it is just a console based application.

The final output main menu screen that appears on our terminal has the following below features:-
	1. Add Showrooms
	2. Add Employees
	3. Add Cars
	4. Get Showrooms
	5. Get Employees
	6. Get Cars

The Showroom class here is made parent of Employee class and the Cars class having 
hierarchical inheritance.

**  Showroom Class **

In showroom class we are implementing  an interface named "Utility". Interface provide some methods that we can implement in our classes and we have to override these methods when we implement them in our class.

In out code we are having two functions which are -->> 
	1. get details( ) - prints all the data related to the showroom to the console.
	2. Set details( ) - takes input from the user and stores them to the respective variables.

** Employee Class **

Learning-
	a. "class Employee extends Showroom implements Utility" - correct statement.
	b. "class Employee implements utility extends Showroom " - wrong statement.

This is because we cannot implement an interface without inheriting a class we cannot implement an interface.

In employee class again we are having different variables which will store different values as per entered by the user and the two respective functions here are doing the same work as that in Showroom class.

Note:- In our code, the employee id is made with the help of "UUID". It is a class in java which provides a unique id for every employee. There is no need for us to set  id for first employee and increase it by one every time, it just generates a random unique id every time.

Another point here is, we are not having any database connectivity, it is just a console based application.

** Cars Class ** 

With having the same functions and some respective variables, it will provide us some features to choose like fuel type diesel or petrol, car type which can be Sedan, SUV or Hatchback, car transmission which can be automatic or manual.

Note:- Since we have implemented interface so it is must for us to override it.

** Main Function **

Showroom showroom[ ] = new Showroom[5];
Employees employee[ ] = new Employees[5];
Cars car[ ] = new Cars[5];

By the above three lines in the main function code we understood that instead of making multiple objects, we passed array to object of the class and having some size and with the help of their indices we can access the respective object.

Intially we have set a value of 5, when we will be connecting the database, the we will not need it.

In our code we are having counter variables whose value will increase when we will add a detail and after 5 it will throw out of bound exception.

int choice = 100 is the random no. taken by us not used anywhere in the code and further we implemented switch case.
Our switch case is having different choices in our code.

Note:-
Showroom[showroom_counter] showroom = new Showroom[5]; //  this statement means we are dealing with that index that is the current value of this variable.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
