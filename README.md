## Task1
#Task1 for online internship 

###1.sum of two numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
print("Sum =", a + b)

##output 
Enter first number: 5
Enter second number: 7
Sum = 12

###2.odd or even checker
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even number")
else:
    print("Odd number")

  ##output 
Enter a number: 9
Odd number


###3.factorial calculation
n = int(input("Enter a number: "))
fact = 1
for i in range(1, n + 1):
    fact = fact * i
print("Factorial =", fact)

##output 
Enter a number: 5
Factorial = 120

###4.Fibonacci sequence 
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

 ##output 
 Enter number of terms: 7
Fibonacci sequence:
0 1 1 2 3 5 8


###5.String Reverse
text = input("Enter a string: ")
print("Reversed string:", text[::-1])

##output 
Enter a string: python
Reversed string: nohtyp


###6.palindrome check
word = input("Enter a word: ")
if word == word[::-1]:
    print("Palindrome")
else:
    print("Not a Palindrome")

##output 
Enter a word: madam
Palindrome


###7.Leap year check
year = int(input("Enter a year: "))
if (year % 400 == 0) or (year % 4==0 and year % 100 != 0):
    print("Leap Year")
else:
    print("Not a Leap Year")

##output 
Enter a year: 2024
Leap Year


###8.Armstrong number
num = int(input("Enter a number: "))
temp = num
sum = 0
while temp > 0:
    digit = temp % 10
    sum += digit ** 3
    temp //= 10
if sum == num:
    print("Armstrong Number")
else:
    print("Not an Armstrong Number")

##output 
Enter a number: 153
Armstrong Number
