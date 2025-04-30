# Exp.No:3c
## LIST - APPEND NUMBERS IN LIST

---

### AIM  
To write a Python function that takes a list 'L' as an argument, adds 5 in all the odd values and 10 in all the even values of the list L. Also display the list L.

---

### ALGORITHM

1.Start

2.Define a function modify_list(L)

3.For each element num in the list L:

4.If num is even (num % 2 == 0), add 10

5.Else (odd), add 5

6.Replace the original value in the list with the new value

7.Display the modified list

8.End

---

### PROGRAM

```
def add(n):
l=[]
for i in n:
if i%2!=0:
i+=5
l.append(i)
else:
i+=10
l.append(i)
print(l)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/341d03a6-0863-4ea5-96b6-5619964d8e84)

### RESULT
Thus,the given python program is implemented and executed sucessfully.
