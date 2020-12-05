# IS_Project
#todo: add project description

## Authors
- Suhail Lala
- Kathryn Mitchell
- Komla Nyagbe

## Using the Program
- The program comes with a console prompt for easy use. Simply run the program and the command line will appear. 
```
Welcome! Enter a formula or type ? to view commands
```
- To see the different commands and symbols, type `?`. To see documentation on a specific command, type `help <command_name>`.
```
(Cmd) ?

Documented commands (type help <topic>):
========================================
exit  help  formula
```
```
(Cmd) help exit
Exit the command shell
```
- To determine if a given formula is a tautology, run `formula(<input>)`. For example, running `formula('S1,A,(A->(B->C))->((A->B)->(A->C)),S2')` will return:
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
