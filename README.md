# Toy Language Interpreter
An interpreter for a Toy programming language written in Java with a graphical user interface

## Used concepts and Technical Features
- Graphical User Interface built using JavaFX
- Layered architecture
- Use of multi-threading
- Implementations for several common expressions and statements used in programming
- Exceptions handling
- Java streams

## Instructions:
- logical expressions
- arithmetical expressions
- relational expressions
- variable declaration & assignment
- printing
- if
- while
- file opening, closing and reading
- fork (multi-threading)
- heap allocation, reading and writing

## Variables Types:
- Bool
- Int
- String
- Reference

## Functionalities
- Storing instructions in execution stacks
- Storing local variables in symbol tables
- Storing BufferedReader objects into a file table used for file operations
- Shared heap across all the states created by a program - allocation, reading, writing and garbage collector
- Storing printing output in an output table
- While forking, a new program state is being created with a unique ID 
- Program states: each state has a unique ID, a symbol table and an execution stack

# GUI
- a window to select the programs
- a window to execute the selected program
<p align="center"> <img src="https://github.com/AndreiGota/ToyLanguageInterpreter/blob/master/images/Capture1.PNG" height="500"/> </p>
<p align="center"> <img src="https://github.com/AndreiGota/ToyLanguageInterpreter/blob/master/images/Capture2.PNG" height="500"/> </p>
