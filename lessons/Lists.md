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
