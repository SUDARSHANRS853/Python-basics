1. ## Largest of a given number
```
a = 23
b = 4
c = 5
d= 28
e= 349
largest = max(a, b, c,d,e)
print("Largest number is:", largest)
```
```
num = [23, 4, 5, 28, 349]
maximum = num[0]
for n in num:
    if maximum<n:
        maximum=n
print('Largest number is:',maximum)
```
Output
```
Largest number is:349 
```
2. ## Lowest of a give number
```
a = 23
b = 4
c = 5
d= 28
e= 349
minimum= min(a, b, c,d,e)
print("lowest number is:", largest)
```
```
num = [23, 4, 5, 28, 349]
minimum = num[0]
for n in num:
    if minimum>n:
        minimum=n
print('Minimum number is:',minimum)
```

Output
```
Lowest number is: 4
```
3. ## even number detector
```
num= int(input('enter a number:'))
if num%2==0:
    print('entered number %d is odd')
print('entered number %d is odd')
```
Output
```
enter a number:14
entered number %d is even
```
4. ## odd number detector
```
num= int(input('enter a number:'))
if num%2!=0:
    print('entered number %d is odd')
else:
    print('entered number %d is even')
```
Output
```
enter a number:23
entered number %d is odd
```


