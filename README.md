# hangman
A hangman text-based game made in C

# Build instructions
Build this with gcc doing the following: 
gcc -o hangman.out main.c libs/hangfunc.c
You can change "hangman.out" for anything you like.

# Wordlist instructions
You can change the wordlist, just make sure the first line of the file is the numeber of lines - 1.
For example:
The default 3words.hwl has a 50 lines, so the first line is the number 49.
