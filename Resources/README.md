## Table_of_Contents

- [Online IDE](#online_ide)
- [Python Resources](#python_resources)
- [Other Resources](#other_resources)
- [Python Mathematical Functions](#python_mathematical_functions)
- [Python Keywords](#python_keywords)
- [Python String Methods](#python_string_methods)
- [Python List Methods](#Python_List_Methods)
- [Python Dictionary Methods](#Python_Dictionary_Methods)
- [Python Tuple Methods](#Python_Tuple_Methods)
- [Python Set Methods](#Python_Set_Methods)

---

## Online_IDE

<a href="https://repl.it/" target="_blank">Repl: in-browser IDE</a>

<a href="https://glot.io/" target="_blank">glot.io: in-browser IDE</a>

[back](#Table_of_Contents)

---

## Python_Resources

<a href="https://docs.python.org/3/library/functions.html" target="_blank">Built-in Functions</a>

<a href="https://realpython.com/python-comments-guide/" target="_blank">Comments Guide</a>

<a href="https://www.makeuseof.com/tag/python-instance-static-class-methods/" target="_blank">Instance vs. Static vs. Class Methods</a>

<a href="https://docs.python.org/3/reference/datamodel.html#special-method-names" target="_blank">Special method names</a>

<a href="https://docs.python.org/3/library/exceptions.html" target="_blank">Built-in Exceptions</a>

<a href="https://docs.python.org/3/py-modindex.html" target="_blank">Python Module Index</a>

<a href="https://pypi.org/" target="_blank">PyPI</a>

[back](#Table_of_Contents)

---

## Other_Resources

<a href="https://passwordsgenerator.net/sha1-hash-generator/" target="_blank">SHA1 Hash Generator</a>

<a href="https://www.pythonanywhere.com/" target="_blank">Host, run, and code Python</a>

<a href="http://www.mashup-template.com/templates.html" target="_blank">HTML Templates 1</a>

<a href="https://hatchful.shopify.com/" target="_blank">Logo Maker</a>

[back](#Table_of_Contents)

---

## Python_Mathematical_Functions

```python
import math
```
| Key | Description |
| --- | --- |
| ceil(x)|Returns the smallest integer greater than or equal to x.|
| copysign(x, y)|Returns x with the sign of y|
| fabs(x)|Returns the absolute value of x|
| factorial(x)|Returns the factorial of x|
| floor(x)|Returns the largest integer less than or equal to x|
| fmod(x, y)|Returns the remainder when x is divided by y|
| frexp(x)|Returns the mantissa and exponent of x as the pair (m, e)|
| fsum(iterable)|Returns an accurate floating point sum of values in the iterable|
| isfinite(x)|Returns True if x is neither an infinity nor a NaN (Not a Number)|
| isinf(x)|Returns True if x is a positive or negative infinity|
| isnan(x) | Returns True if x is a NaN |
| ldexp(x, i) | Returns x * (2 * * i) |
| modf(x) | Returns the fractional and integer parts of x |
| trunc(x) | Returns the truncated integer value of x |
| exp(x) | Returns e * * x |
| expm1(x) | Returns e * * x - 1 |
| log(x[, base]) | Returns the logarithm of x to the base (defaults to e) |
| log1p(x) | Returns the natural logarithm of 1+x |
| log2(x) | Returns the base-2 logarithm of x |
| log10(x) | Returns the base-10 logarithm of x |
| pow(x, y) | Returns x raised to the power y |
| sqrt(x) | Returns the square root of x |
| acos(x) | Returns the arc cosine of x |
| asin(x) | Returns the arc sine of x |
| atan(x) | Returns the arc tangent of x |
| atan2(y, x) | Returns atan(y / x) |
| cos(x) | Returns the cosine of x |
| hypot(x, y) | Returns the Euclidean norm, sqrt(x*x + y*y) |
| sin(x) | Returns the sine of x |
| tan(x) | Returns the tangent of x |
| degrees(x) | Converts angle x from radians to degrees |
| radians(x) | Converts angle x from degrees to radians |
| acosh(x) | Returns the inverse hyperbolic cosine of x |
| asinh(x) | Returns the inverse hyperbolic sine of x |
| atanh(x) | Returns the inverse hyperbolic tangent of x |
| cosh(x) | Returns the hyperbolic cosine of x |
| sinh(x) | Returns the hyperbolic cosine of x |
| tanh(x) | Returns the hyperbolic tangent of x |
| erf(x) | Returns the error function at x |
| erfc(x) | Returns the complementary error function at x |
| gamma(x) | Returns the Gamma function at x |
| lgamma(x) | Returns the natural logarithm of the absolute value of the Gamma function at x |
| pi | Mathematical constant, the ratio of circumference of a circle to it's diameter (3.14159...) |
| e | mathematical constant e (2.71828...) |

[back](#Table_of_Contents)

---

## Python_Keywords

| Key | Description |
| --- | --- |
| and	| A logical operator |
| as | To create an alias |
| assert | For debugging |
| break | To break out of a loop |
| class | To define a class |
| continue | To continue to the next iteration of a loop |
| def | To define a function |
| del | To delete an object |
| elif | Used in conditional statements, same as else if |
| else | Used in conditional statements |
| except | Used with exceptions, what to do when an exception occurs |
| False | Boolean value, result of comparison operations |
| finally | Used with exceptions, a block of code that will be executed no matter if there is an exception or not |
| for | To create a for loop |
| from | To import specific parts of a module |
| global | To declare a global variable |
| if | To make a conditional statement |
| import | To import a module |
| in | To check if a value is present in a list, tuple, etc. |
| is | To test if two variables are equal |
| lambda | To create an anonymous function |
| None | Represents a null value |
| nonlocal | To declare a non-local variable |
| not | A logical operator |
| or | A logical operator |
| pass | A null statement, a statement that will do nothing |
| raise | To raise an exception |
| return | To exit a function and return a value |
| True | Boolean value, result of comparison operations |
| try | To make a try...except statement |
| while | To create a while loop |
| with | Used to simplify exception handling |
| yield | To end a function, returns a generator |

[back](#Table_of_Contents)

---

## Python_String_Methods

| Key | Description |
| --- | --- |
| capitalize() | Converts the first character to upper case |
| casefold() | Converts string into lower case |
| center() | Returns a centered string |
| count() | Returns the number of times a specified value occurs in a string |
| encode() | Returns an encoded version of the string |
| endswith() | Returns true if the string ends with the specified value |
| expandtabs() | Sets the tab size of the string |
| find() | Searches the string for a specified value and returns the position of where it was found |
| format() | Formats specified values in a string |
| format_map() | Formats specified values in a string |
| index() | Searches the string for a specified value and returns the position of where it was found |
| isalnum() | Returns True if all characters in the string are alphanumeric |
| isalpha() | Returns True if all characters in the string are in the alphabet |
| isdecimal() | Returns True if all characters in the string are decimals |
| isdigit() | Returns True if all characters in the string are digits |
| isidentifier() | Returns True if the string is an identifier |
| islower() | Returns True if all characters in the string are lower case |
| isnumeric() | Returns True if all characters in the string are numeric |
| isprintable() | Returns True if all characters in the string are printable |
| isspace() | Returns True if all characters in the string are whitespaces |
| istitle() | Returns True if the string follows the rules of a title |
| isupper() | Returns True if all characters in the string are upper case |
| join() | Joins the elements of an iterable to the end of the string |
| ljust() | Returns a left justified version of the string |
| lower() | Converts a string into lower case |
| lstrip() | Returns a left trim version of the string |
| maketrans() | Returns a translation table to be used in translations |
| partition() | Returns a tuple where the string is parted into three parts |
| replace() | Returns a string where a specified value is replaced with a specified value |
| rfind() | Searches the string for a specified value and returns the last position of where it was found |
| rindex() | Searches the string for a specified value and returns the last position of where it was found |
| rjust() | Returns a right justified version of the string |
| rpartition() | Returns a tuple where the string is parted into three parts |
| rsplit() | Splits the string at the specified separator, and returns a list |
| rstrip() | Returns a right trim version of the string |
| split() | Splits the string at the specified separator, and returns a list |
| splitlines() | Splits the string at line breaks and returns a list |
| startswith() | Returns true if the string starts with the specified value |
| strip() | Returns a trimmed version of the string |
| swapcase() | Swaps cases, lower case becomes upper case and vice versa |
| title() | Converts the first character of each word to upper case |
| translate() | Returns a translated string |
| upper() | Converts a string into upper case |
| zfill() | Fills the string with a specified number of 0 values at the beginning |

[back](#Table_of_Contents)

---

## Python_List_Methods

| Key | Description |
| --- | --- |
| append() | Adds an element at the end of the list |
| clear() | Removes all the elements from the list |
| copy() | Returns a copy of the list |
| count() | Returns the number of elements with the specified value |
| extend() | Add the elements of a list (or any iterable), to the end of the current list |
| index() | Returns the index of the first element with the specified value |
| insert() | Adds an element at the specified position |
| pop() | Removes the element at the specified position |
| remove() | Removes the first item with the specified value |
| reverse() | Reverses the order of the list |
| sort() | Sorts the list |

[back](#Table_of_Contents)

---

## Python_Dictionary_Methods

| Key | Description |
| --- | --- |
| clear() | Removes all the elements from the dictionary |
| copy() | Returns a copy of the dictionary |
| fromkeys() | Returns a dictionary with the specified keys and value |
| get() | Returns the value of the specified key |
| items() | Returns a list containing a tuple for each key value pair |
| keys() | Returns a list containing the dictionary's keys |
| pop() | Removes the element with the specified key |
| popitem() | Removes the last inserted key-value pair |
| setdefault() | Returns the value of the specified key. If the key does not exist: insert the key, with the specified value |
| update() | Updates the dictionary with the specified key-value pairs |
| values() | Returns a list of all the values in the dictionary |

[back](#Table_of_Contents)

---

## Python_Tuple_Methods

| Key | Description |
| --- | --- |
| count() | Returns the number of times a specified value occurs in a tuple |
| index() | Searches the tuple for a specified value and returns the position of where it was found |

[back](#Table_of_Contents)

---

## Python_Set_Methods

| Key | Description |
| --- | --- |
| add() | Adds an element to the set |
| clear() | Removes all the elements from the set |
| copy() | Returns a copy of the set |
| difference() | Returns a set containing the difference between two or more sets |
| difference_update() | Removes the items in this set that are also included in another, specified set |
| discard() | Remove the specified item |
| intersection() | Returns a set, that is the intersection of two other sets |
| intersection_update() | Removes the items in this set that are not present in other, specified set(s) |
| isdisjoint() | Returns whether two sets have a intersection or not |
| issubset() | Returns whether another set contains this set or not |
| issuperset() | Returns whether this set contains another set or not |
| pop() | Removes an element from the set |
| remove() | Removes the specified element |
| symmetric_difference() | Returns a set with the symmetric differences of two sets |
| symmetric_difference_update() | inserts the symmetric differences from this set and another |
| union() | Return a set containing the union of sets |
| update() | Update the set with the union of this set and others |

[back](#Table_of_Contents)
