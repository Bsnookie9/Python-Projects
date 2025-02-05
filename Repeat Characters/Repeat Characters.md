# Description
Create a Python function that accepts and returns a string, with each character in the original string doubled. 

If you send the function “now” as a parameter, it should return “nnooww,” and if you send “123a!”, it should return “112233aa!!”.

# Solution
```
# Gather user input
word = input("Enter a word: ")

# Number of times to repeat each character
n = 2 

# Loop over the word and repeat each character
for char in word:
    print(char * n, end="")  # concatenate repeated characters

print()  # to ensure there is a newline after the final output
```

# My Thoughts

This was a bit of a struggle at first when trying to get each char but once I got that then I multiplied by 2 to double each char.

Essentially just loop over each char in the word and multiply it n times (# of times you assign).

Hope you enjoyed :) :)
