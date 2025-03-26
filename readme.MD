Word Count CLI
A simple CLI tool to count word occurrences in a text file. This tool allows you to easily analyze the frequency of words in a given file and optionally search for a specific word.

## Installation
You can use this tool via installing it globally or locally.
You can install it globally for frequent use.

- Global Installation:

        npm install -g count-easily 

If you install this globally you can use it any file in your pc.

- Local Installation:

        npm install  count-easily

If you install this locally you can use it on only installed file in your pc.

## How to use it ?

        npx count-easily <file-path> <keyword>

Where:

< file-path>: Path to the text file you want to analyze.

< keyword>: (Optional) A specific word you want to count. If not provided, the tool will count all words in the file.




# Example:

Given a ( test.txt ) file for testing purpose : 


Running:

        npx count-easily test.txt

- Would output :
Word frequency in the file: { this: 2, is: 2, a: 1, test: 1, file: 2, for: 1, testing: 1, purposes: 1 }


 If you search for a specific word:

        npx count-easily test.txt testing

- Would output :
The word "testing" appeared 1 time(s) in the file.



