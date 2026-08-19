# A. Classes and Objects — 5 Questions

## Question 1 — Student Result Management

Create a Java class `Student` to represent a university student. The class should store the student's registration number, name, semester, and marks obtained in three subjects. Use a parameterized constructor to initialize all student information.

Implement methods to calculate the total marks, percentage, and final grade. Assume each subject carries 100 marks. The grade should be assigned according to the following criteria: 80% and above = A, 70% to 79% = B, 60% to 69% = C, 50% to 59% = D, and below 50% = F.

Also create a method to display the complete student information including registration number, name, semester, total marks, percentage, and grade. In the `main()` method, create at least two `Student` objects and display their results.


## Question 2 — Bank Account Management

Create a Java class `BankAccount` to represent a customer's bank account. The class should contain the account number, account holder name, account type, and current balance.

Use a parameterized constructor to initialize these values. Implement methods `deposit()` and `withdraw()` to allow a customer to perform transactions. The `deposit()` method should reject zero or negative amounts, while the `withdraw()` method should only allow a transaction when the requested amount is positive and sufficient balance is available.

Create another method to display the account details and current balance. In the `main()` method, create two bank account objects, perform multiple deposit and withdrawal operations, and display their final balances.


## Question 3 — Employee Salary System

Create a Java class `Employee` for storing information about employees working in an organization. The class should store employee ID, employee name, basic salary, and number of overtime hours worked.

Use a parameterized constructor to initialize all employee information. Assume that each overtime hour is paid at a rate of 500. Implement methods to calculate overtime payment, gross salary, tax, and net salary. Deduct 10% tax if the gross salary is greater than 100,000; otherwise deduct 5%.

Create a method to display a complete salary slip. In the `main()` method, create at least two employees and display their salary information.


## Question 4 — Library Book Management

Create a Java class `Book` to represent books available in a library. The class should store the book ID, title, author name, price, and availability status.

Use a parameterized constructor to initialize a new book. Implement a method `issueBook()` that changes the availability status when a book is issued. A book that is already issued should not be issued again.

Implement another method `returnBook()` that makes the book available again. Also create a method to display complete book information.

In the `main()` method, create multiple `Book` objects and demonstrate issuing and returning books.


## Question 5 — Student Course and SGPA System

Create Java classes `Student`, `Course`, and `Grade`. A `Student` can register for a maximum of five courses. The `Course` class should store course information such as course code, course title, and credit hours, while the `Grade` class should store the marks for each course using a parameterized constructor.

Implement appropriate methods to determine the letter grade and grade points from the marks. Use the following grading scheme: 85 and above = A with 4.0 grade points, 80–84 = A- with 3.7, 75–79 = B+ with 3.3, 70–74 = B with 3.0, 65–69 = B- with 2.7, 60–64 = C+ with 2.3, 55–59 = C with 2.0, 50–54 = D with 1.0, and below 50 = F with 0.0.

Calculate the student's Semester GPA (SGPA) using the credit hours and grade points of all registered courses. The program should display the student's registration number, name, course details, marks, grades, grade points, and final SGPA.


# B. Inheritance — 5 Questions

## Question 6 — Person, Student, and Teacher

Create a Java class `Person` that stores common information including name, age, CNIC, and address. Derive two classes, `Student` and `Teacher`, from the `Person` class.

The `Student` class should additionally store registration number, semester, and CGPA, while the `Teacher` class should store employee ID, department, and salary.

Use parameterized constructors in all classes and use the `super` keyword to initialize inherited properties. Implement separate methods in `Student` and `Teacher` to display their complete information.

In the `main()` method, create one student and one teacher and demonstrate how the child classes inherit the properties of `Person`.


## Question 7 — Vehicle Inheritance System

Create a Java parent class `Vehicle` that stores common information about a vehicle including registration number, brand, model, and speed.

Derive two child classes `Car` and `Motorcycle` from `Vehicle`. The `Car` class should additionally store the number of doors and seating capacity, while the `Motorcycle` class should store engine capacity and whether the motorcycle has a self-start feature.

Use parameterized constructors and the `super` keyword to initialize common properties. Implement appropriate methods to display complete information for each vehicle.

Create one object of each child class and demonstrate single-level and hierarchical inheritance.


## Question 8 — Employee, Developer, and Senior Developer

Create a multilevel inheritance structure using the classes `Employee`, `Developer`, and `SeniorDeveloper`.

The `Employee` class should store employee ID, name, and basic salary. The `Developer` class should inherit from `Employee` and additionally store the programming language and project allowance. The `SeniorDeveloper` class should inherit from `Developer` and store a team allowance and number of team members supervised.

Implement a method in `SeniorDeveloper` to calculate the total monthly salary by adding the basic salary, project allowance, and team allowance.

Use parameterized constructors at each inheritance level and demonstrate constructor chaining using `super`. Display the complete details of a senior developer in the `main()` method.


## Question 9 — University Employee System

Create a parent class `UniversityEmployee` containing employee ID, name, and basic salary. Derive two classes `Faculty` and `AdministrativeStaff`.

The `Faculty` class should store designation and number of courses taught. It should calculate a teaching allowance of 5,000 for every course taught.

The `AdministrativeStaff` class should store department name and number of overtime hours. Each overtime hour should be paid at 700.

Implement appropriate methods in both child classes to calculate their total salary. Use inheritance to reuse the common employee information and display the complete salary details of one faculty member and one administrative employee.


## Question 10 — Product and Electronic Product

Create a parent class `Product` containing product ID, product name, price, and quantity. Derive a class `ElectronicProduct` that additionally contains brand name, warranty period in years, and a discount percentage.

Implement a method in the child class to calculate the total price according to quantity and then apply the discount. For example, if the unit price is 50,000, quantity is 2, and discount is 10%, the final payable amount should be calculated after applying the discount on the total price.

Use parameterized constructors and inheritance appropriately. Create at least two electronic product objects and display their complete details and final prices.

# C. Method Overloading — 5 Questions

## Question 11 — Calculator Using Method Overloading

Create a Java class `Calculator` that demonstrates compile-time polymorphism using method overloading.

Create multiple methods with the same name `calculate()` but different parameter lists. One method should add two integer values, another should add three integer values, another should multiply two `double` values, and another should calculate the average of four `double` values.

Call each overloaded method from the `main()` method and display the returned values. The objective is to demonstrate how Java selects an overloaded method according to the number and type of arguments passed.


## Question 12 — Area Calculator Using Overloading

Create a Java class `AreaCalculator` that calculates the area of different geometric shapes using overloaded methods named `area()`.

Implement one method that accepts one integer parameter and calculates the area of a square. Implement another method that accepts two integer parameters and calculates the area of a rectangle. Implement another method that accepts a `double` radius and calculates the area of a circle. Finally, implement a method that accepts a base and height as `double` values and calculates the area of a triangle.

Demonstrate all overloaded versions in the `main()` method and display the calculated areas.


## Question 13 — Student Information Using Overloaded Methods

Create a Java class `Student` with an overloaded method named `display()`.

The first version of `display()` should accept only the student's name. The second version should accept name and registration number. The third version should accept name, registration number, and semester. The fourth version should additionally accept CGPA.

Call each overloaded method using different sets of arguments and observe how the Java compiler determines the appropriate method based on the method signature.


## Question 14 — Product Discount Using Method Overloading

Create a Java class `Product` that calculates the final price of a product using overloaded methods named `calculatePrice()`.

One version of the method should accept only the product price and return it without any discount. A second version should accept the price and discount percentage and calculate the discounted amount. A third version should accept price, quantity, and discount percentage and calculate the total discounted price for multiple units.

Demonstrate all versions in the `main()` method.


## Question 15 — Employee Salary Calculation Using Overloading

Create a Java class `SalaryCalculator` that demonstrates method overloading using methods named `calculateSalary()`.

The first method should accept only a basic salary. The second method should accept basic salary and bonus. The third method should accept basic salary, bonus, and overtime payment. The fourth method should accept basic salary, bonus, overtime payment, and tax percentage and return the final salary after tax deduction.

Create different employee salary calculations in the `main()` method by calling the overloaded methods with different arguments.



# D. Method Overriding — 5 Questions

## Question 16 — Employee Salary Using Method Overriding

Create a parent class `Employee` containing employee ID, employee name, and basic salary. Define a method named `calculateSalary()` that returns the basic salary.

Derive two classes `Manager` and `Developer` from `Employee`. The `Manager` class should additionally store a management allowance and override `calculateSalary()` to return the basic salary plus management allowance.

The `Developer` class should store a project allowance and overtime amount and override the same method to return the basic salary plus project allowance and overtime.

Create objects of both child classes and demonstrate how the same method produces different results depending on the object.


## Question 17 — Shape Area Using Method Overriding

Create a parent class `Shape` containing a method named `calculateArea()`. The parent implementation may return `0`.

Create subclasses `Rectangle`, `Circle`, and `Triangle`. Each child class should store the dimensions required for its respective shape and override `calculateArea()` to provide the correct area calculation.

Use a `Shape` reference to hold objects of all three child classes one at a time and call the overridden method. Demonstrate runtime polymorphism by showing that Java executes the method of the actual object rather than the reference type.


## Question 18 — Bank Interest Rate System

Create a parent class `Bank` containing a method named `getInterestRate()`. The parent method should return a default interest rate.

Create three subclasses named `SavingsBank`, `CommercialBank`, and `IslamicBank`. Override the `getInterestRate()` method in each class to return a different interest or profit rate.

Also implement a method that calculates the annual return on a given deposited amount using the overridden rate. Use parent class references to store objects of different banks and display the calculated annual returns to demonstrate runtime polymorphism.


## Question 19 — Transportation Fare Calculation

Create a parent class `Transport` containing a method `calculateFare(int distance)`. The parent implementation may return zero.

Derive three classes `Bus`, `Taxi`, and `Train`. Override the fare calculation method according to the following rules: a bus charges 20 per kilometer, a taxi charges 50 per kilometer plus a fixed base fare of 100, and a train charges 15 per kilometer.

Use a `Transport` reference to calculate the fare for the same travel distance using different transport objects. Display the fare charged by each type of transport.


## Question 20 — University Grading System Using Runtime Polymorphism

Create a parent class `Assessment` containing assessment title, total marks, and obtained marks. Define a method named `calculatePercentage()` and another method named `displayResult()`.

Create subclasses `Assignment`, `Midterm`, and `FinalExam`. Override `displayResult()` in each subclass so that it displays the assessment type, marks obtained, percentage, and appropriate status.

For an `Assignment`, the student passes with at least 50%. For a `Midterm`, the student passes with at least 50%. For a `FinalExam`, the student must obtain at least 60% to pass.

Create an array of `Assessment` references containing objects of all three subclasses. Traverse the array and call `displayResult()` to demonstrate method overriding and runtime polymorphism.


