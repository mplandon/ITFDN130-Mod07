# User Defined Functions                                                                                                                                                           

## Introduction
This paper will explain a when to use a SQL User Defined Function (UDF) and the differences between Scalar, Inline, and Multi-Statement Functions. 

## SQL UDF
A SQL UDF is used to create custom functions and can be used with multiple select statements where you can define the column and data types. A calculation that is repeated throughout a database is an example of when a SQL UDF would be used. A SQL UDF can also be used with a check restraint as shown in meeting date and time demonstration.

## Differences Between Scalar, Inline, and Multi-Statement Functions
The differences between Scalar, Inline, and Multi-Statement functions are: Scalar functions returns a single value and use Begin and End Block, Inline functions return a table based on a single select statements and do not use the Begin and End Block,  Multi-Statement Functions also return a table, but one or more selects statements can be used, the Return Table is Declared, and uses the Begin and End Block.

## Summary
In summary, this paper explained when a SQL UDF would be used. The differences between the three types of SQL UDF: Scalar, Inline, and Multi-Statement were also explained  
