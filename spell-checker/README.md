# Make a Spell Checker!

Write a program that checks spelling. The input to the program is a dictionary file containing a list of valid words and a file containing the text to be checked.

The program should run on the command line like so:

```text
<path to your program> dictionary.txt file-to-check.txt
# output here
```

Your program should support the following features (time permitting):

- The program outputs a list of incorrectly spelled words.
- For each misspelled word, the program outputs a list of suggested words.
- The program includes the line and column number of the misspelled word.
- The program prints the misspelled word along with some surrounding context.
- The program handles proper nouns (person or place names, for example) correctly.


## Technical Details

- The formatting of the output is up to you, but try to make it easy to understand.
- The dictionary file (`dictionary.txt` in the example above) is a plain text file with a word per line.
- You can use the `dictionary.txt` file included here as your dictionary.
- The input file (`file-to-check.txt` in the example above) is a plain text file that may contain full sentences and paragraphs.
- You should come up with your own content to run through the spell checker.
- Feel free to use any programming language, but extra credit for using Java or Kotlin.
- Someone from Voze will review the code with you, so be prepared to discuss your code.
