# Homework 3: The Password Game

## ➜ [The password game](https://neal.fun/password-game/)

## Due date: Tuesday, February 24

## Overview

In this homework, we will use Z3 -- in particular,
the Z3 string and regular expression data types --
to implement a solver for the first 10 levels of the password game
(link above).

Before you start, try the password game yourself,
to get a sense of how it works.

As with HW2, you will need to have Z3 installed (see [Homework 0](https://github.com/DavisPL-Teaching/189c-hw0)).

As with HW1 and HW2, you will submit your homework through GitHub Classroom.
Clone your copy of the repository, then add, commit, and push your changes to GitHub before the deadline.
For detailed instructions, see [this Piazza post](https://piazza.com/class/lt90i40zrot3ue/post/48).

## Task

Your task is to fill in `password.py` with a Z3 program that solves the first 10 levels of the password game.
When run, the program will print out a password satisfying all the cosntraints for each of the first 10 levels.
The file contains further instructions.

## Getting help

### Regex help

A successful solution will use the Z3 API for string and regular expression (Regex) types. We have include a file `regex_help.md` that provides some help with some of the available regular expression operators in Z3 that you may need to use.

### ASCII table

You will also need to reference the ASCII table to understand
how certain chracters in a string are encoded.
You can find an ASCII table online or in `ascii_table.txt`.

### Hints

If you get stuck, take a look at the `hints.md` file for some hints on how to proceed.

### Piazza

As always, please ask questions on Piazza or drop by office hours!
