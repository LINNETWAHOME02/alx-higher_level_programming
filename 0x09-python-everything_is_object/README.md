# Python - Everything is object


In this project, I studied object instantiation in Python, delving into variable aliasing and object identifiers, types, and mutability. The project involved a series of quiz-like questions the answers to which I provided in single-line `.txt` files.


## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files.

## TASKS :

* **0. Who am I?**
What function would you use to print the type of an object?


* **1. Where are you?**
How do you get a variable's identifier (which is the memory address in the CPython implementation)?

* **2. Right count**
In the following code, do `a` and `b` point to the same object?
```
>>> a = 89
>>> b = 100
```

* **3. Right count =**
 In the following code, do `a` and `b` point to the same object?
```
>>> a = 89
>>> b = 89
```

* **4. Right count =**
 In the following code, do `a` and `b` point to the same object?
```
>>> a = 89
>>> b = a
```

* **5. Right count =+**
 In the following code, do `a` and `b` point to the same object?
```
>>> a = 89
>>> b = a + 1
```

* **6. Is equal**
 What do these 3 lines print?
```
>>> s1 = "Best School"
>>> s2 = s1
>>> print(s1 == s2)
```

* **7. Is the same**
 What do these 3 lines print?
```
>>> s1 = "Best"
>>> s2 = s1
>>> print(s1 is s2)
```

* **8. Is really equal**
 What do these 3 lines print?
```
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 == s2)
```

* **9. Is really the same**
 What do these 3 lines print?
```
>>> s1 = "Best School"
>>> s2 = "Best School"
>>> print(s1 is s2)
```

* **10. And with a list, is it equal**
 What do these 3 lines print?
```
>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3]
>>> print(l1 == l2)
```

* **11. And with a list, is it the same**
*  What do these 3 lines print?
```
>>> l1 = [1, 2, 3]
>>> l2 = [1, 2, 3]
>>> print(l1 is l2)
```

* **12. And with a list, is it really equal**
 What do these 3 lines print?
```
>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 == l2)
```

* **13. And with a list, is it really the same**
 What do these 3 lines print?
```
>>> l1 = [1, 2, 3]
>>> l2 = l1
>>> print(l1 is l2)
```

* **14. List append**
 What does this script print?
```
l1 = [1, 2, 3]
l2 = l1
l1.append(4)
print(l2)
```

* **15. List add**
 What does this script print?
```
l1 = [1, 2, 3]
l2 = l1
l1 = l1 + [4]
print(l2)
```

* **16. Integer incrementation**
 What does this script print?
```
def increment(n):
    n += 1

a = 1
increment(a)
print(a)
```

* **17. List incrementation**
 What does this script print?
```
def increment(n):
    n.append(4)

l = [1, 2, 3]
increment(l)
print(l)
```

* **18. List assignation**
 What does this script print?
```
def assign_value(n, v):
    n = v

l1 = [1, 2, 3]
l2 = [4, 5, 6]
assign_value(l1, l2)
print(l1)
```

* **19. Copy a list object**
 Python function `def copy_list(l):` that returns a copy of a list.

* **20. Tuple or not?**
 Is `a` a tuple?
```
a = ()
```

* **21. Tuple or not?**
 Is `a` a tuple?
```
a = (1, 2)
```

* **22. Tuple or not?**
 Is `a` a tuple?
```
a = (1)
```

* **23. Tuple or not?**
 Is `a` a tuple?
```
a = (1, )
```

* **24. Who I am?**
 What does this script print?
```
a = (1)
b = (1)
a is b
```

* **25. Tuple or not**
 What does this script print?
```
a = (1, 2)
b = (1, 2)
a is b
```

* **26. Empty is not empty**
 What does this script print?
```
a = ()
b = ()
a is b
```

* **27. Still the same**
 Will the last line of this script print `139926795932424`?
```
>>> id(a)
139926795932424
>>> a
[1, 2, 3, 4]
>>> a = a + [5]
>>> id(a)
```

* **28. Same or not?**
 Will the last line of this script print `139926795932424`?
```
>>> a
[1, 2, 3]
>>> id (a)
139926795932424
>>> a += [4]
>>> id(a)
```

* **29. #pythonic**
 Python function `magic_string()` that returns the string `"BestSchool"` n times the number of iteration.

* **30. Low memory cost**
 Python class `LockedClass` with no attributes that prevents the user from dynamically creating any new instance attributes not called `first_name`.

* **31. int 1/3**
 How many `int` objects are created by the execution of the first line in this script?
 How many `int` objects are created by the execution of the second line in this script?
```
a = 1
b = 1
```

* **32. int 2/3**
 How many `int` objects are created by the execution of the first line in this script?
 How many `int` objects are created by the execution of the second line in this script?
 After the execution of line 3, is the `int` object pointed to by `a` deleted?
 After the execution of line 4, is the `int` object pointed to by `b` deleted?
 How many `int` objects are created by the execution of the last line in this script?
```
a = 1024
b = 1024
del a
del b
c = 1024
```

* **33. int 3/3**
 Before the execution of line 2 in this script, how many `int` objects have been created and are still in memory?
```
print("I")
print("Love")
print("Python")
```

* **34. Clear strings**
 How many `str` objects are created by the execution of the first line in this script?
 How many `str` objects are created by the execution of the second line in this script?
 After the execution of line 3, is the `str` object pointed to by `a` deleted?
 After the execution of line 4, is the `str` object pointed to by `b` deleted?
 How many `str` objects are created by the execution of the last line in this script?
```
a = "SCHL"
b = "SCHL"
del a
del b
c = "SCHL"
```
