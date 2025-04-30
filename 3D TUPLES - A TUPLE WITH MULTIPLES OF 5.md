# Exp.No:3d  
## TUPLES - REMOVE THE ELEMENTS OF THE TUPLE
---

### AIM  
To write a python function that a string, convert it into a tuple and remove the 3rd element of the tuple.

---

### ALGORITHM

1.Start

2.Input a string from the user

3.Convert the string to a tuple (each character becomes an element)

4.Check if the tuple has at least 3 elements

5.If yes, remove the element at index 2

6.Else, skip removal

7.Return/Display the modified tuple

8.End

---

### PROGRAM

```
def strtotuple(a):
t=tuple(a)
print(t)
l=list(t)
b=l[2]
l.pop(2)
t1=tuple(l)
print(t1)
print(f"Character Removed: {b}")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/e2ad234a-4394-42d8-9b33-e15fb9d42d85)

### RESULT
Thus,the given python program is implemented and executed sucessfully.
