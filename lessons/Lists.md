# What is List?

lists are a separate data type that can store a different number of data types.
to create a list, you must use square brackets (`` [] ``). 
all list items are comma separated (2, 6, 'Hello', 'A', 5)

# What is the difference between a list and an array?

For example, an array can contain only one kind of data type. 
The list can also contain items of only one type. But it is perfectly acceptable for the same list to contain both numbers and strings.

#

```py
a = [1, 2, 3, 4, 5]
```
You can also convert other types of data to a list.
```py
>>> a = list('1234')
>>> a
['1', '2', '3', '4']
```

#

To refer to the elements of the list, you need to use their indices. List item indexing starts at 0.
that is, the first element of the list will have index `0` and the second `1`.
To start indexing from the end you need to use negative numbers(-1, -4).
```py
a = [1, 'hi', 'car', 6, 'A']
print(a[0])
print(a[1])
print(a[-3])
```

Modifying list items.
```py
a[0] = 'plane'
```
In this case, the first element of the list has been replaced with 'plane'

Now you need to do something with the list. Basic built-in functions are available for lists, as well as list methods.

* `list.append(N)` Adds an item to the end of the list
 ```
 >>> list = [2, 5, 'car']
 >>> print(list.append(4))
 [2, 5, 'car', 4]
 ```
 #
* `list.extend(N)` Expands list by adding all the elements of N to the end 
```
>>> list = []
>>> list.extend('add')
>>> print(list)
['a', 'd', 'd']
```
#

* `list.insert(a, x)` Inserts the value x on the a-th element
```
>>> list = [1, 3]
>>> list.insert(1, 2)
>>> print(list)
[1, 2, 3]
```
#
* `list.remove(x)` Removes the specified element from the list.
```
>>> list = [1, 2, 3, 4, 'phone', 5]
>>> list.remove('phone')
>>> print(list)
[1, 2, 3, 4, 5]
```
#

* `list.pop(i)` Returns the element at the specified position by removing it from the list.
```
>>> list = [1, 2, 3, 4, 5]
>>> popped1 = list.pop() # 5
>>> list 
[1, 2, 3, 4]
```
Here we see that the last element of the list is removed and entered into the variable (popped1), in addition, we can work with the removed element.

To remove an element by index, you need to put the index you need in brackets
```
>>> list = [1, 2, 3, 4, 5]
>>> popped2 = list.pop(-3) # 2
>>> list
[1, 2, 4, 5]
```
#

* `list.index(x, i)` a built-in list method that lets you know the index or position of an element.
Simply put, this method looks for an item in the list and returns it

```
>>> list = [1, 2, 3, 4, 5]
>>> list.index(2)
1
```
if you specify an element that does not exist in the list, then it will return an error: ValueError

#
* `list.count(x)` returns the number of elements x

```
>>> list = [1, 2, 3, 4, 5, 2]
>>> list.count(2)
2
```

#

* `list.sort()` Sorts the list items in ascending order.

```
>>> list = [1, 2, 3, 4, 5, 2]
>>> list.sort()
>>> list
[1, 2, 2, 3, 4, 5]
```
You can also sort the list in descending order.

```
>>> list = [1, 2, 3, 4, 5, 2]
>>> list.sort(reverse=True)
>>> list
[5, 4, 3, 2, 2, 1]
```

#

* `list.reverse()` rearranges the elements of the list in reverse order.

```
>>> list = [1, 'red', 'a', 4]
>>> list.reverse()
>>> list
[4, 'a', 'red', 1]
```

#

* `list.copy()` shallow copy of list

```
>>> list = [1, 4, 2, 'green', 6]
>>> copy_list = list.copy()
>>> copy_list
[1, 4, 2, 'green', 6]
```

#

* `list.clear()` clears the list

 ```
>>> list = ['1', '32', 5, 8, 1]
>>> list.clear()
>>> list
[]
 ```
 An empty list is displayed
