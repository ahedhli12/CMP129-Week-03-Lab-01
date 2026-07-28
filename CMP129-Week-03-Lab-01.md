CMP 129 – Computer Science II
Week 3 – Lab 1: Classes, Validation, and Overloaded Constructors
Learning Objectives

After completing this lab, students should be able to:

Define classes with private instance variables.
Create constructors to initialize objects.
Overload constructors using different parameter lists.
Use getter and setter methods.
Validate values before storing them.
Create and test multiple objects.
Display object information in a formatted manner.

Complete both programming problems. Create separate Java files as specified.

Problem 1: Date Class

Create a class named Date that stores a date using three private integer attributes:

month
day
year
Date Class Requirements

Create:

Date.java

The class must include:

A constructor that accepts the month, day, and year.
Getter and setter methods for all three attributes.
Input validation for the month and day.
Methods that display the date in three different formats.
Input Validation
The month must be between 1 and 12.
The day must be between 1 and 31.
If an invalid value is supplied, display an appropriate error message and do not store the invalid value.

For this assignment, you do not need to validate the exact number of days in a particular month.

Display Methods

Create the following methods:

displayNumeric()
displayMonthFirst()
displayDayFirst()

The methods should produce output similar to:

12/25/2014
December 25, 2014
25 December 2014

Use a selection structure or an array to convert the numeric month into its corresponding month name.

DateTest Class

Create:

DateTest.java

In its main method:

Create at least two Date objects.
Display each date in all three formats.
Use setter methods to update at least one date.
Test the month and day validation using invalid values.
Use getter methods to retrieve at least one stored value.
Problem 2: Employee Class

Create a class named Employee that stores information about an employee.

Employee Attributes

The class must contain these private attributes:

String name
int idNumber
String department
String position
Required Constructors

Create three overloaded constructors.

Constructor 1: All Attributes
public Employee(
    String name,
    int idNumber,
    String department,
    String position
)

This constructor must initialize all four attributes.

Constructor 2: Name and ID Number
public Employee(String name, int idNumber)

This constructor must:

Initialize name and idNumber.
Assign an empty string to department.
Assign an empty string to position.
Constructor 3: Default Constructor
public Employee()

This constructor must:

Assign empty strings to name, department, and position.
Assign 0 to idNumber.
Getter and Setter Methods

Create getter and setter methods for every attribute:

getName()
setName()
getIdNumber()
setIdNumber()
getDepartment()
setDepartment()
getPosition()
setPosition()

Create a method named:

displayInfo()

It must display all information for one employee in a clear, formatted manner.

EmployeeTest Class

Create:

EmployeeTest.java

In its main method, create these three employees:

Name	ID number	Department	Position
Susan Meyers	47899	Accounting	Vice President
Mark Jones	39119	IT	Programmer
Joy Rogers	81774	Manufacturing	Engineer

Use each overloaded constructor at least once:

Create one employee using the constructor with all four arguments.
Create one employee using the constructor with the name and ID number.
Create one employee using the default constructor.
Use setter methods to complete any missing employee information.
Use getter methods to retrieve at least one value.
Call displayInfo() for each employee.
General Requirements
Keep all class attributes private.
Put each public class in a separate Java file.
Do not place the main method inside Date.java or Employee.java.
Use the this keyword where appropriate.
Follow standard Java naming conventions.
Use meaningful variable and object names.
Include comments explaining constructors, validation, and important methods.
Indent and format the code correctly.
Test every constructor, getter, setter, and display method.
Both programs must compile and run without errors.
You must be able to explain every part of your submitted code.
Follow the course AI-use policy.
Record any AI assistance in AI-Use-Report.md.
Required Organization
Week-03
└── Lab-01
    ├── CMP129-Week-03-Lab-01.docx
    ├── AI-Use-Report.md
    └── src
        ├── Date.java
        ├── DateTest.java
        ├── Employee.java
        └── EmployeeTest.java

The four Java files may initially contain only this starter comment:

/*
 * Student Name:
 * Course: CMP 129
 * Week: 3
 * Lab: 1
 * Problem:
 * Date:
 */

Use these problem labels:

Problem 1 – Date Class
Problem 2 – Employee Class
Submission

Push these files to the Week 3 GitHub repository:

Lab-01/src/Date.java
Lab-01/src/DateTest.java
Lab-01/src/Employee.java
Lab-01/src/EmployeeTest.java
Lab-01/AI-Use-Report.md

Make at least two meaningful commits, such as:

Complete Date class with validation
Add Employee constructors and test program
