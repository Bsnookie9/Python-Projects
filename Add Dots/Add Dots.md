# Description

Write a function in Python that accepts a string. The function should return a string and add “.” in between each letter. 

For example, if you send the function “skills” as a parameter, it should return “s.k.i.l.l.s”.

# Solution

```
# Define the dots function
def add_dots(string):
  return ".".join(string)

# Gather user input
word = add_dots(input("Enter a word: "))

# Use input as parameter for function
print(word)
```

# My Thoughts

This project was very straightforward. Create a function where you take the string and join a "." to each position.

Then gather the user input and pass that parameter through the function and print the result.

Straightforward problems are the best. Enjoy :) :)
