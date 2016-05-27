# Programming Exercise - Grouping

The goal of this exercise is to identify rows in a CSV file that
may represent the __same person__ based on a provided **matching type** (definition below).

The resulting program should allow us to test at least three matching types:
 - one that matches records with the same email address
 - one that matches records with the same phone phone number
 - one that matches records with the same email address OR the same phone number

## Guidelines

* Use any language you want, as long as it can be compiled on OSX
* Don't use any code that you don't have license to use
* Don't hesitate to ask us any questions to clarify the project
* For the exercise, headers are considered to be consistent across files

## Resources

### CSV Files

Three sample input files are included. All files should be successfully
processed by the resulting code.

### Matching Type

A matching type is a declaration of what logic should be used to compare the rows.

For example: A matching type named same_email might make use of an algorithm that 
matches rows based on email columns.

## Interface

At a high level, the program should take two parameters. The input file
and the matching type.

## Output

The expected output is a copy of the original CSV file with the unique 
identifier of the person each row represents prepended to the row.
