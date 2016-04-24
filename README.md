Falkonera
=========
falkonera - converts CSV file(s) into DDL and DML statements for a relational database

Syntax
======
falkonera [OPTIONS]... [INPUTFILE] -d [DDL OUTPUT FILE] -m [DML OUTPUT FILE] -e [ERROR LOG FILE]


options:

-h: help

-c: comment character (default: #)

-r: record separator  (default: CR)

-s: value separator   (default: comma)

-q: quote character (default: ")

-n: first line does NOT contain column names  (default: first line contains column names)

-t: table name (default: import)

-x: SQL syntax (default: mysql)

Example
=======
falkonera example.csv -d example.ddl -m example.dml

reads csv-file, using names in first line as column name and generating "create table"-statement into example.ddl.
remaining lines are transformed into insert-statements and put into example.dml






