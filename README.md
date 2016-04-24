Falkonera
=========
falkonera - converts CSV file(s) into DDL and DML statements for a relational database

Syntax
======
falkonera [OPTIONS]... [INPUTFILE] -l [DDL OUTPUT FILE] -m [DML OUTPUT FILE] -e [ERROR LOG FILE]


options:

-h: help

-r: record separator  (default: CR)

-s: value separator   (default: comma)

-c: comment character (default: #)

-n: first line does NOT contain column names  (default: first line contains column names)

-x: SQL syntax (default: mysql)

Example
=======
falkonera 

