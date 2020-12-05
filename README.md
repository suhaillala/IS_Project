# IS_Project
#todo: add project description

## Authors
- Suhail Lala
- Kathryn Mitchell
- Komla Nyagbe

## Using the Program
- The program comes with a console named "schema" for easy use. Simply run the program and the command line will appear. 
```
Welcome! Enter a schema or type ? to view commands
```
- To see the different commands, type `?`. To see documentation on a specific command, type `help <command_name>`.
```
(Cmd) ?

Documented commands (type help <topic>):
========================================
example  exit  help  schema
```
```
(Cmd) help example
Display input and output of an example schema.
```
- To determine if a given schema is a tautology, run `schema(<input>)`. For example, running `schema('S1,A,→→A→BC→→AB→AC,S2')` will return:
```
('S1,A,A,A,~A,C,S2') : Fundamental
('S1,A,A,~B,~A,C,S2') : Fundamental
('S1,A,B,A,~A,C,S2') : Fundamental
('S1,A,B,~B,~A,C,S2') : Fundamental
('S1,A,~C,A,~A,C,S2') : Fundamental
('S1,A,~C,~B,~A,C,S2') : Fundamental
Given formula is a Tautology
```
- To exit the program, type `exit`.
