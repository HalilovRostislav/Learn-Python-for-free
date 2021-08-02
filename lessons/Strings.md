# What is Strings?

Strings are an ordered sequence of characters. Used to store text information.
To create a string, you must enclose the character or characters in single(`'`) or double(`"`) quotes. For example, "Hello world!"

# Can number be a string?

Yes we can. Put the main number in quotes.
we can see that the numbers in the variables are not enclosed in quotes because it is not a string, but of type int (integer data type
). If the value in the variable is not enclosed in quotes, then it is not a string. We can also find out what type of data the value belongs to: 

We can also find out the data type of the value for this we can use the `type()` function, `print(type(10))`, output: `<class 'int'>` shows that `10` belongs to the class `int`(int is short for integer). we can still find out the type of the string: `print(type("plane"))`, output: `<class 'str'>` str is short for string

# how to concatenate strings,

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
In this case, the comma serves as a space for us when concatenating strings. If you are trying to concatenate values ​​with different data types, you will get an error message, to avoid this, you need a comma.
