# Hide the Credit Card Number  

Write a function in Python that accepts a credit card number. It should return a string where all the characters are hidden with an asterisk except the last four.  

For example, if the function gets sent “4444444444444444”, then it should return “************4444”.

# Solution

```
# gathering input from the user
input_cc_num = input("Enter your credit card number (Format: xxxxxxxxxxxxx): ")

# replacement char
K = "*"

# using len() and * operator to solve the problem
cc_num = K * (len(input_cc_num) - 4) + input_cc_num[-4:]

print("Your credit card number is: " + cc_num)
```

# My Thoughts

This was an interesting little code to do.

I struggled a bit to grab the correct number of characters from the string based on indiex placement, but in the end I got it to print the way it would read on a receipt. Hope you enjoy!
