# Give Me the Discount

Create a function in Python that accepts two parameters. The first should be the full price of an item as an integer. The second should be the discount percentage as an integer.

The function should return the price of the item after the discount has been applied. For example, if the price is 100 and the discount is 20, the function should return 80.

# Solution

```
# define integer check function
def is_integer(value):
    try:
        int(value)
        return True
    except ValueError:
        return False

# gathering inputs from the user and validate it is an integer
while True:
    full_price = input("Enter full price of item (as an integer): ")
    if is_integer(full_price):
        full_price = int(full_price)
        break
    else:
        print(f"{full_price} is not an integer. Please enter an integer!")

while True:
    discount = input("Enter the discount amount (as an integer): ")
    if is_integer(discount):
        discount = int(discount)
        d_percent = discount / 100
        final_price = int(full_price - (full_price * d_percent))  # convert to integer here
        print(f"The final price after discount is: {final_price}")
        break
    else:
        print(f"{discount} is not an integer. Please enter an integer!")
```

# My Thoughts

Integers and strings are frustrating sometimes. However, once you have them converted they way you need them, the functions work great hahahahaha!

This was a fun little project, taking user input, validating that the input is an integer, and then calculating the final price. Hope you like it :)
