# Palindrome Finder (Ada)
Ada coursework that takes strings from a text file or user input, determines their palindrome status, and then informs the user. If something is not initially a palindrome, the program converts to uppercase and/or removes symbols to see if a palindrome exists underneath.

Potential palindromes are as follows:
- racecar
- Eve (becomes a palindrome after conversion to uppercase)
- Eve!!! (becomes a palindrome after conversion to uppercase and symbol removal)

# Instructions for use from command line
- gnatmake pal_finder.adb
- ./pal_finder < filename (reads from specified text file in appropriate format)

# Input/Output
By supplying various strings in the text file, the program will output the following:
```
String: "sample"
Status: Not a palindrome
```
```
String: "PuP"
Status: Palindrome as entered
```
```
String: "$$#$"
Status: Palindrome when non-letters are removed
Characters removed: 4
```
and so forth.

**Ada compiler can be found here**
[GNAT Community Edition](https://www.adacore.com/download)
