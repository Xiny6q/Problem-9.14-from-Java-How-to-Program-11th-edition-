Download link :https://programming.engineering/product/problem-9-14-from-java-how-to-program-11th-edition/

# Problem-9.14-from-Java-How-to-Program-11th-edition-
Problem 9.14 from Java How to Program (11th edition)
In this chapter, you studied an inheritance hierarchy in which class BasePlusCommissionEmployee inherited from class CommissionEmployee.

However, not all types of employees are CommissionEmployees.

In this exercise, you’ll create a more general Employee superclass that factors out the attributes and behaviors in class CommissionEmployee that are common to all Employees.

The common attributes and behaviors for all Employees are firstName, lastName, socialSecurityNumber, getFirstName, getLastName, getSocialSecurityNumber and a portion of method toString.

Create a new superclass Employee that contains these instance variables and methods and a constructor.

Next, rewrite class CommissionEmployee from Section 9.4.5 as a subclass of Employee.

Class CommissionEmployee should contain only the instance variables and methods that are not declared in superclass Employee.

Class CommissionEmployee’s constructor should invoke class Employee’s constructor, and CommissionEmployee’s toString method should invoke Employee’s to-String method.

Once you’ve completed these modifications, run the CommissionEmployeeTest and BasePlusCommissionEmployeeTest apps using these new classes to ensure that the apps still display the same results for a CommissionEmployee object and BasePlusCommissionEmployee object, respectively.

by Paul Deitel & Harvey Deitel
