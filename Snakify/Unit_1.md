# 1. Input, print and numbers
  «Sum of three numbers»
  
  ```.py
  a = int(input())
  b = int(input())
  c = int(input())
  print(a + b + c)
  ```

  «Hi John»
  
  ```.py
  name = input()
  greet = "Hi " + name
  print(greet)
  ```
  
  «Square»
  
  ```.py
  numb = int(input())
  print(numb ** 2)
  ```
  
  «Area of right-angled triangle»
  
  ```.py
  # Read the numbers b and h like this:
  b = int(input())
  h = int(input())
  print(b*h/2)
  ```
  «Hello, Harry!»
  
  ```.py
  name = input()  + '!'
  greeting = "Hello,"
  print(greeting, name,)
  ```
  
  «Apple sharing»
  
  ```.py
  n = int(input())
k = int(input())
t = (k-k // n*n)
print(k // n)
print(t)
  ```
  
  «Previous and next»
  
  ```.py
  a = int(input())
nxt = a + 1
pre = a - 1
print('The next number for the number ' + str(a) + ' is ' + str(nxt) + '.')
print('The previous number for the number ' + str(a) + ' is ' + str(pre) + '.')
  ```
  
  «Two timestamps»
  
  ```.py
  h = int(input())
m = int(input())
s = int(input())
h2 = int(input())
m2 = int(input())
s2 = int(input())
H = h2 - h
M = m2 - m
S = s2 - s
real = H*3600 + M*60 + S
print(real)
  ```
  
  «School desks»
  
  ```.py
  a = int(input())
b = int(input())
c = int(input())

A = a % 2
B = b % 2
C = c % 2
A2 = a // 2
B2 = b // 2
C2 = c // 2

true = A+B+C+A2+B2+C2

print(true)
  ```
