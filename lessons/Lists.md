# What is List?

lists are a separate data type that can store a different number of data types.
to create a list, you need to use square brackets (```[]```).
```py
a = [1, 2, 3, 4, 5]
```
you can also use the ```list()``` constructor to create a list.
```py
a = list()
```

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

* list.append(N) Adds an item to the end of the list
 ```
 >>> list = [2, 5, 'car']
 >>> print(list.append(4))
 [2, 5, 'car', 4]
 ```
 #
* list.extend(N) Expands list by adding all the elements of N to the end 
```
>>> list = []
>>> list.extend('add')
>>> print(list)
['a', 'd', 'd']
```
#

* list.insert(a, x) Inserts the value x on the a-th element
```
>>> list = [1, 3]
>>> list.insert(1, 2)
>>> print(list)
[1, 2, 3]
```
#
* list.remove(x) Removes the specified element from the list.
```
>>> list = [1, 2, 3, 4, 'phone', 5]
>>> list.remove('phone')
>>> print(list)
[1, 2, 3, 4, 5]
```


* list.pop ([i]) Removes the i-th element and returns it. If no index is specified, the last element is removed
* list.index(x, [start [, end]]) Returns the position of the first element with value x (searching from start to end)
* list.count(x) Returns the number of items with value x
* list.sort([key = function]) Sorts the list based on the function
* list.reverse() Expands the list
* list.copy() A shallow copy of the list
* list.clear() Clears the list
