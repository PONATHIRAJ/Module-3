# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
a=int(input())

b=[i for i in range(5,a) if i%5==0]

print(tuple(b))
```

### OUTPUT
![image](https://github.com/user-attachments/assets/64f3d4f1-a82b-4ba2-8bde-d294802bf905)

### RESULT
Thus the Python program to create a tuple containing all multiples of 5 up to a given number **N** is successfully implemented and executed.
