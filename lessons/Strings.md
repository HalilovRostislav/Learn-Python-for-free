# What is String?

The string is an ordered sequence of characters. Used to store text information. To create a string, you must enclose the character or characters in single(') or double(") quotes. For example, "Hello world!"

# Can number be a string?

Yes. Put the main number in quotes.
we can see that the numbers in the variables are not enclosed in quotes because it is not a string, but of type int (integer data type
). If the value in the variable is not enclosed in quotes, then it is not a string.  

We can also find out the data type of the value for this we can use the `type()` function, `print(type(10))`, output: `<class 'int'>` shows that `10` belongs to the class `int`(int is short for integer). we can still find out the type of the string: `print(type("plane"))`, output: `<class 'str'>` str is short for string

# How to concatenate strings

We can concatenate strings using the `+` symbol.

```
>>> "Hello " + "world"
Hello world
```

#

```
>>> 'Hi', 'Jake!'
Hi Jake!
```
In this case, the comma serves as space for us when concatenating strings. If you are trying to concatenate values ​​with different data types, you will get an error message, to avoid this, you need a comma.
