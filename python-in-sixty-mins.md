# Python in Sixty Minutes

This Python guide, much like the others you find on the Internet or in textbooks should cover everything you need to know to begin simple software development in Python. The caveat is that it will be a shortform and bitesized version of the 500 page book you will usually grab to read.

This book is not aimed at any particular audience but should hope to serve nicely for a gentle and brief introduction to the wonderful language of Python.

If you do not already have Python and or an IDE/text editor on your system, please follow the instructions under [Appendix [Where do I Begin]](#appendix-where-do-i-begin)

## Hello Reader - What's Your Name?

The program below demonstrates printing content to the terminal. `print()` can be passed any arguments you wish to display on a single line.

```python
print("Hello Reader...")
```

Not everything has to be some one-time value in programming, you can store values in memory using **variables**. Much like in maths, these are some sort of named value you wish to refer to because it is easier than rewriting a long equation. You can see in Code-Snippet 2 that we first assign the value `"ice cream"` to the variable named `favourite_food`. Next we assign two other variables, the first being an integer and the second being a floating-point number (a decimal in normal Maths).

You can then pass those variables around and amend them, such as here we are printing our `favourite_food` to the terminal.

```python
favourite_food = "ice cream"
number_of_pets = 4
pi = 3.14

print("I like ", favourite_food)
```

### Interact!

Not only can you display something to the terminal, you can take user input too! The `input()` function will pause the program and wait for a user to type followed by a Carriage-Return. Once entered, the function will return the value. Here we are capturing that return value into a variable to use later.

```python
print("Hello Reader...")
reader_name = input("What is your name? ")
print("I like the name ", reader_name, "!")
```

## Back to Maths Class

Python, much like other languages comes built-in with basic arithmetic operations (exciting right?).

| Operation         | Symbol | Example Equation |
|:-----------------:|:------:|:-----------------|
| Addition          | +      | 5 = 3 + 2        |
| Subtraction       | -      | 7 = 10 - 3       |
| Multiplication    | *      | 15 = 5 / 3       |
| Division          | /      | 8 = 64 / 8       |
| Integer-Division  | //     | 2 = 10.5 / 5     |
| Modulo            | %      | 1 = 21 % 2       |
| Exponent          | **     | 25 = 5^2         |


## Appendix

### Appendix [Where do I Begin]