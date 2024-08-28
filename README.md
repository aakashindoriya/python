# Python String and Array (List) Methods

This document provides a quick reference to common string and array (list) methods in Python. Use this guide to familiarize yourself with the available methods for manipulating strings and arrays.

## String Methods

| Method               | Description                                                                 | Example                                      |
|----------------------|-----------------------------------------------------------------------------|----------------------------------------------|
| `str.upper()`        | Converts all characters in the string to uppercase.                         | `"hello".upper()` -> `"HELLO"`               |
| `str.lower()`        | Converts all characters in the string to lowercase.                         | `"HELLO".lower()` -> `"hello"`               |
| `str.capitalize()`   | Capitalizes the first character of the string.                              | `"hello".capitalize()` -> `"Hello"`          |
| `str.title()`        | Capitalizes the first letter of each word in the string.                    | `"hello world".title()` -> `"Hello World"`   |
| `str.strip()`        | Removes leading and trailing whitespace from the string.                    | `" hello ".strip()` -> `"hello"`             |
| `str.split(sep)`     | Splits the string into a list of substrings based on a delimiter `sep`.      | `"a,b,c".split(",")` -> `['a', 'b', 'c']`    |
| `str.join(iterable)` | Joins elements of an iterable with the string as the separator.              | `"".join(['a', 'b', 'c'])` -> `"abc"`        |
| `str.replace(old, new)` | Replaces occurrences of `old` with `new` in the string.                 | `"hello".replace("l", "x")` -> `"hexxo"`     |
| `str.find(sub)`      | Returns the lowest index of the substring `sub` in the string.              | `"hello".find("e")` -> `1`                   |
| `str.startswith(prefix)` | Returns `True` if the string starts with the specified prefix.         | `"hello".startswith("he")` -> `True`         |
| `str.endswith(suffix)` | Returns `True` if the string ends with the specified suffix.             | `"hello".endswith("lo")` -> `True`           |
| `str.count(sub)`     | Returns the number of non-overlapping occurrences of `sub` in the string.   | `"hello".count("l")` -> `2`                  |

## Array (List) Methods

| Method               | Description                                                                 | Example                                      |
|----------------------|-----------------------------------------------------------------------------|----------------------------------------------|
| `list.append(x)`     | Adds an item `x` to the end of the list.                                     | `[1, 2, 3].append(4)` -> `[1, 2, 3, 4]`      |
| `list.extend(iterable)` | Extends the list by appending elements from the iterable.                | `[1, 2].extend([3, 4])` -> `[1, 2, 3, 4]`    |
| `list.insert(i, x)`  | Inserts an item `x` at a given position `i`.                                 | `[1, 2, 3].insert(1, 10)` -> `[1, 10, 2, 3]` |
| `list.remove(x)`     | Removes the first item from the list whose value is `x`.                     | `[1, 2, 3, 2].remove(2)` -> `[1, 3, 2]`      |
| `list.pop([i])`      | Removes and returns the item at position `i` (default is the last item).     | `[1, 2, 3].pop()` -> `[1, 2]`                |
| `list.clear()`       | Removes all items from the list.                                             | `[1, 2, 3].clear()` -> `[]`                  |
| `list.index(x)`      | Returns the index of the first occurrence of `x` in the list.                | `[1, 2, 3].index(2)` -> `1`                  |
| `list.count(x)`      | Returns the number of times `x` appears in the list.                         | `[1, 2, 2, 3].count(2)` -> `2`               |
| `list.sort()`        | Sorts the list in ascending order.                                           | `[3, 1, 2].sort()` -> `[1, 2, 3]`            |
| `list.reverse()`     | Reverses the elements of the list in place.                                  | `[1, 2, 3].reverse()` -> `[3, 2, 1]`         |
| `list.copy()`        | Returns a shallow copy of the list.                                          | `list.copy()` -> `[1, 2, 3]`                 |
| `len(list)`          | Returns the number of items in the list.                                     | `len([1, 2, 3])` -> `3`                      |
| `list(enumerate())`  | Adds a counter to the list and returns it as an enumerate object.            | `list(enumerate(['a', 'b']))` -> `[(0, 'a'), (1, 'b')]` |
| `in` (Membership Test) | Checks if an item exists in the list.                                      | `2 in [1, 2, 3]` -> `True`                   |

## Additional Resources

For more detailed information, you can refer to the official Python documentation:
- [String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)
- [List Methods](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
