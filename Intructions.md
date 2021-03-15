#Intructions

Please write a function that will take in a text file path as a command line arg and output a text file in the same directory. The function should calculate the word frequency of the input file and write to the output file the 50 most frequent words and their frequencies.  The output should be ordered from most frequent to least frequent.


####Example 

_Input File_

```
The foo the foo the
defenestration the
```

_Corresponding Output File_
```
the 4
foo 2
defenestration 1
```

##Problem Scope and assumptions:

* Normalize words to lowercase: "The the THE" should be "the 3" in the output
* For the purpose of this problem, a word is anything seperated by whitespace. Treat any punctuation as part of the word
* If the frequency of two words is the same, the output order does not matter
* You may only use the starndard library for the language of your choice

You may check your solution against the provided file _output50.txt_ using a command line diff tool, or diffchecker.com

``` 
cmp output50.txt yourOutput.txt
```

