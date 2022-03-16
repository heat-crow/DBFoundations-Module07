Heather Crowder
March 15, 2022
Foundations of Databases & SQL Programming
Assignment 07
(https://github.com/heat-crow/DBFoundations-Module07/)

#SQL Functions

##Introduction
Within SQL, there are a variety of functions including aggregate functions and user defined functions (UDF). Aggregate functions allow the programmer to perform calculations on multiple values and returns a single value. Aggregate functions can be used to determine minimum, maximum, average and total values. Aggregate functions are for math calculations within SQL. Another type of function utilized within SQL is a user defined function. UDFs take data, manipulates it and then provides a result of the manipulated data. 

##Using SQL UDFs
User defined functions (UDFs) are used within SQL Server to return either a single scalar value or a result set. By using an UDF, programmers can store the function once but use it multiple times. Another benefit of utilizing UDFs is faster execution of code. Within UDFs, errors cause the function to stop and the selection statement to be canceled. 

##Scalar, Inline, and Multi-Statement Functions
User defined functions (UDFs) can provide an output of either a single value or a data set.  A scalar function is an UDF that returns a single value when run. They are used to simplify SQL code. When modifying scalar functions, the actions used include Create, Alter and Drop. 
Inline functions produce a returned value by using a single statement. These functions are unique in that they are similar to SQL views. Inline functions use select statements and do not use begin-end. Parameters are used within inline functions. The structure of the results table is determined by the select statement.
Multi-statement functions contain a series of statements that return a single table. By using a multi-statement function, users are able to modify information within the function to produce more complicated results. The results table structure is determined by the user. 

##Summary
Functions are simply explained as chunks of code that can be used multiple times. Each function performs a specific task. Aggregate functions complete mathematical computations such as finding the sum or average of the data. User defined functions (UDFs) can provide the user with either a single value (scalar function) or a data set (inline functions or multi-statement functions). Functions are stored once but can be executed multiple times.  Using functions allow the code to be executed faster as an additional benefit.
