# IS_Project
This program uses the RS-Method to determine if a given propositional calculus formula is a tautology. Two types of schemas are tested: S1/S2 and S1/(S2;S3), where S1 is given as a premise and S2,S3 are given as conclusions. For each inputted formula, the program returns yes/no output.

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
- To determine if a given formula is a tautology, run `formula <input>`. For example, running `formula S1,~A,~(A -> C) -> (~(C v D) -> (A ^ C)), S2` will return:
```
S1,~A,~A,C,C,D,A,S2 : Fundamental
S1,~A,~A,C,C,D,C,S2 : Not Fundamental
Given formula is not a Tautology
```
- To exit the program, type `exit`.

### In this program:
- Atomic statements are A, B, C, D and E.
- Symbols are (~, ->, v, ^)
- S1, S2, S3 etc. denote indecomposable formulas
