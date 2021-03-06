# Data output. print() function

print() is a function that prints what is in its parentheses to the screen.
We will talk more about the function later.


```
>>> print(10000)
10000
>>> print(3.43)
2.34
>>> print("Hello, World!")
Hello, World!
```

Any data type can be in brackets.
Also, the amount of data can be any amount.
In print () function you can create string concatenation using ```+``` sign

.

```
>>> print("Hello, " + "Jake")
Hello, Jake
```

```
>>> print("X:", 1)
X: 1
>>> print("My name is", "Rostik")
My name is Rostik
```
in this case the string ```X:``` and the digit ```1``` are concatenated.
The comma (```,```) in this case serves us as a space and allows us to connect elements of different data types.

print() provides additional parameters. Using the ```sep``` parameter, you can specify a line separator other than a space.

```
>>> print('Monday', 'Thuesday', 'Wednesday', sep='-')
Monday-Thuesday-Wednesday
```

The end parameter allows you to specify what to do after the line is printed. By default, a line break occurs. However, this action can be undone by specifying any other character

```
>>> print(10, end="")
10
>>> print(32, end="\n\n")

>>>
```

the input () function is responsible for outputting to the keyboard input program

```
>>> a = input()
3
>>> a
'3'
```

```
>>> x = input()
Hi!
>>> print(x)
Hi!
```
Note that the program is supplied with a string. Even if you enter a number, the input () function will still return its string. 
Type conversion functions can be used to solve this problem.

```
>>> a = int(input())
```
in this situation, the user can only enter values ​​of type int (integer data type)
