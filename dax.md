
# PowerBI kurs 09.11.2022

## 1 - Noen DAX formler

### 1.1 [SELECTCOLUMNS](https://learn.microsoft.com/en-us/dax/selectcolumns-function-dax)

*Returns a table with selected columns from the table and new columns specified by the DAX expressions.*

### 1.2 [SUMMARIZE](https://learn.microsoft.com/en-us/dax/summarize-function-dax)

*Returns a summary table for the requested totals over a set of groups.*

### 1.3 [UNION](https://learn.microsoft.com/en-us/dax/union-function-dax)

*Creates a union (join) table from a pair of tables.*

### [EVALUATE](https://dax.guide/st/evaluate/)

*Used in DAX Studio to enclose evaluate expressions such as `UNION`*

EVALUATE is a DAX statement that is needed to execute a query. EVALUATE followed by any table expression returns the result of the table expression. Moreover, one or more EVALUATE statements can be preceded by special definitions like local tables, columns, measures, and variables that have the scope of the entire batch of EVALUATE statements executed together.
