

# Task 1 – Core Python Challenges
Task1 for online internship

---

## 1. Sum of Two Numbers

### Code
```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum =", a + b)
```

### Output
```
Enter first number: 5
Enter second number: 7
Sum = 12
```

---

## 2. Odd or Even Checker

### Code
```python
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")
```

### Output
```
Enter a number: 9
Odd number
```

---

## 3. Factorial Calculation

### Code
```python
n = int(input("Enter a number: "))
fact = 1
for i in range(1, n + 1):
    fact = fact * i
print("Factorial =", fact)
```

### Output
```
Enter a number: 5
Factorial = 120
```

---

## 4. Fibonacci Sequence

### Code
```python
n = int(input("Enter number of terms: "))
a = 0
b = 1
print("Fibonacci sequence:")
print(a, b, end=" ")
for i in range(2, n):
    c = a + b
    print(c, end=" ")
    a = b
    b = c
```

### Output
```
Enter number of terms: 7
Fibonacci sequence:
0 1 1 2 3 5 8
```

---

## 5. String Reverse

### Code
```python
text = input("Enter a string: ")
print("Reversed string:", text[::-1])
```

### Output
```
Enter a string: python
Reversed string: nohtyp
```

---

## 6. Palindrome Check

### Code
```python
word = input("Enter a word: ")
if word == word[::-1]:
    print("Palindrome")
else:
    print("Not a Palindrome")
```

### Output
```
Enter a word: madam
Palindrome
```

---

## 7. Leap Year Check

### Code
```python
year = int(input("Enter a year: "))
if (year % 400 == 0) or (year % 4 == 0 and year % 100 != 0):
    print("Leap Year")
else:
    print("Not a Leap Year")
```

### Output
```
Enter a year: 2024
Leap Year
```

---

## 8. Armstrong Number

### Code
```python
num = int(input("Enter a number: "))
temp = num
total = 0

while temp > 0:
    digit = temp % 10
    total += digit ** 3
    temp //= 10

if total == num:
    print("Armstrong Number")
else:
    print("Not an Armstrong Number")
```

### Output
```
Enter a number: 153
Armstrong Number
```
