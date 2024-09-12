# Factorial in Python

### Aim
To write a Python program to find the factorial of a number.

### Algorithm
1. start
2. read the number n
3. set fact = 1
4. repeat steps 5 and 6 while i <= n
5. set fact = fact * i
6. set i = i + 1
7. print fact
8. stop

### Code
```python
def factorial(n):
    fact = 1
    for i in range(1, n+1):
        fact = fact * i
    return fact
```

### Main
```python
n = int(input("Enter a number: "))
print("Factorial of", n, "is", factorial(n))
```

### Output
```
Enter a number: 5
Factorial of 5 is 120
```

### Result
The factorial of a number is found and displayed on the console.
