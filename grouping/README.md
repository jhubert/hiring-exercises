# Programming Exercise - Grouping

The goal of this exercise is to identify rows in a CSV file that
may represent the __same person__ based on a provided **matching identifier**.

## Guidelines

* Use any language you want, as long as it can be compiled on OSX
* Don't use any code that you don't have license to use
* For the exercise, headers are considered to be consistent across files

## Resources

### CSV Files

Two sample input files are included. Both files should be successfully
processed by the resulting code.

### Matching Identifier

A matching identifier is an identifying feature used by an algorithm to
compare rows.

For example: same_email would make use of an algorithm that matches rows based
on email columns

## Interface

At a high level, the program should take two parameters. The input file
and the matching type.

## Output

The expected output is a new CSV file that has the original rows marked
with the identifier of the person that row represents.
