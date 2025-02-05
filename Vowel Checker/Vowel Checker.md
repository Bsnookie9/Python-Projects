# Description
Create a function in Python that accepts a single word and returns the vowels found. 

In this function, only a, e, i, o, and u will be counted as vowels — not y.

# Solution
```
# Define list of vowels
vowels = ["a", "e", "i", "o", "u"]

# Gather user input
word = input("Enter a word: ")

# Convert word into a list
w_list = list(word)

# Convert each list to sets and compare
vowel_chars = set(vowels) & set(w_list)

# Check for vowels
if vowel_chars:
    print("Vowels found:", vowel_chars)
else:
    print("No vowels found.")
```

# My Thoughts
This was an easy little project, to be honest. Converting to sets was a step I initially missed, but once I figured that out, everything else fell into place. 

Hope you enjoyed :) :)
