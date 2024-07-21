# Dictionary Program

## Overview
This C++ program performs spell-checking using a hash table data structure. It reads a dictionary file, populates a hash table, and then checks if a user-provided word is spelled correctly. If the word is misspelled, the program suggests corrections based on words with the same starting letters. 

Case 1: The word exists in thee dictionary, the program returns true and suggests other words that start with the same two letters

Case 2: The word is missspelled, but the first letter is in the right position, so it suggests a word and if it is that word it does case 1, but if not it returns false

cae 3: The word dosen't exists, so the program returns false

all other cases: False

## Files

- `main.cpp`: The main C++ program file that includes the spell-checking logic.
- `TimeInterval.h`: Header file for the TimeInterval class used to measure execution time.
- `Dictionary.txt`: Sample dictionary file containing a list of words for spell-checking.

## Compilation

use makefile to compile

make all: Compile
make run: Execute
make clean: Clean up
