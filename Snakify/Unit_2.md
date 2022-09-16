
# 2. Integer and float numbers

### «Last digit of integer»
![]()

```.py
num = int(input())

print(num%10)
```
![]()

### «Two digits»
```.py
num = list(input())
print(num[0])
print(num[1])
```
![]()

### «Swap digits»
```.py
num = list(input())
numb = (num[1]+num[0])
print(numb)
```
![]()

### «Last two digits»
```.py
num = int(input())
print(num%100)
```
![]()

### «Tens digit»
```.py
num = int(input())

num1 = num%100
num2 = num%10
numb = num1 - num2

print(numb//10)
```
![]()

### «Sum of digits»
```.py
num = int(input())
num1 = num%1000//100
num2 = num%100//10
num3 = num%10
print(num1+num2+num3)
```
![]()

### «Reverse three digits»
```.py
num = list(input())

numb = (num[2]+num[1]+num[0])
print(numb)
```
![]()

### «Merge two numbers»
```.py
num0 = list(input())
num1 = list(input())

numb = (num0[0]+num1[0]+num0[1]+num1[1])
print(numb)
```
![]()

### «Cyclic rotation»
```.py
num = list(input())

numb = (num[2]+num[3]+num[0]+num[1])

print(numb)
```
![]()

### «Fractional part»
```.py
import math
num = float(input())

s = math.floor(num)
true = (num - s)
print(true)
```
![]()

### «First digit after decimal point»
```.py
num = float(input())
print(int(num * 10) % 10)
```
![]()

### «Car route»
```.py
from math import ceil

n = int(input())
m = int(input())
print(ceil(m/n))
```
![]()

### «Day of week»
```.py
num = int(input())

num = num +3
num = num %7

print(num)
```
![]()

### «Digital clock»
```.py
num = int(input())

h = num // 60
m = num % 60

print(h, m)
```
![]()

### «Total cost»
```.py
d = int(input())
c = int(input())
tot = int(input())
d2 = d*tot
d3 = c * tot // 100
dol = d2 + d3
cen = c * tot % 100

print(dol, cen)
```
![]()

### «Century»
```.py
y = int(input())

if y%100 == 0:
    print(y//100)
else:
    print(y//100+1)
```
![]()

### «Snail»
```.py
import math

tot = int(input())
A = int(input())
B = int(input())

print(math.ceil((tot - A) / (A - B) + 1))
```
![]()

### «Clock face - 1»
```.py

```
![]()

### «Clock face - 2»
```.py

```
![]()
