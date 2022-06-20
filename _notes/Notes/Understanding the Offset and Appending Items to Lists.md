# List
```py
fruit_list = ["apple ", "oranges"]
```

- list can have mixed data type

## Why zero at the beginning ?
![[Understanding the Offset and Appending Items to Lists 2022-05-16 10.58.41.excalidraw|500]]

- since apple is at the beginning, it has *0 offset* and orange is *1 offset* away from beginning
- If we want to print data from last use **negative  sign**

```py
print(states_of_india[-1])
```
- Even if we don't specify the position of insert, it is always inserted at the end of list
# Using if 
we can use if to check whether particular word or element is in the list
```py
list = ["apple", "oranges", "pinneapple"]
if "apple" in list:
	print{"yes"}
```
## append() to attach at the end of the list

https://docs.python.org/3/tutorial/datastructures.html

The list data type has some more methods. Here are all of the methods of list objects:

```py
list.append(x)
```

Add an item to the end of the list. Equivalent to `a[len(a):] = [x]`.

```py
list.extend(iterable)
```

Extend the list by appending all the items from the iterable. Equivalent to `a[len(a):] = iterable`.

```py
list.insert(i, x)
```

Insert an item at a given position. The first argument is the index of the element before which to insert, so `a.insert(0, x)` inserts at the front of the list, and `a.insert(len(a), x)` is equivalent to `a.append(x)`.

```py
list.remove(x)
```

Remove the first item from the list whose value is equal to _x_. It raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError "ValueError") if there is no such item.

```py
list.pop([i])
```

Remove the item at the given position in the list, and return it. If no index is specified, `a.pop()` removes and returns the last item in the list. (The square brackets around the _i_ in the method signature denote that the parameter is optional, not that you should type square brackets at that position. You will see this notation frequently in the Python Library Reference.)

```py
list.clear()
```

Remove all items from the list. Equivalent to `del a[:]`.

```py
list.index(x, start[, end]])
```

Return zero-based index in the list of the first item whose value is equal to _x_. Raises a [`ValueError`](https://docs.python.org/3/library/exceptions.html#ValueError "ValueError") if there is no such item.

The optional arguments _start_ and _end_ are interpreted as in the slice notation and are used to limit the search to a particular subsequence of the list. The returned index is computed relative to the beginning of the full sequence rather than the _start_ argument.

```py
list.count(x)
```

Return the number of times _x_ appears in the list.


list.sort(_*_, _key=None_, _reverse=False_)

Sort the items of the list in place (the arguments can be used for sort customization, see [`sorted()`](https://docs.python.org/3/library/functions.html#sorted "sorted") for their explanation).

```py
list.reverse()
```

Reverse the elements of the list in place.

```py
list.copy()
```

Return a shallow copy of the list. Equivalent to `a[:]`.


list.extend(list2) adds the elements in list2 to the end of the list. Using + or += on a list is similar to using extend()
```py
list.extend(list2)
```