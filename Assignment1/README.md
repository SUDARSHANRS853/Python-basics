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
5. ## fibonacci series
```
n= int(input('enter the number of terms:'))
a,b=0,1
print('fibanacci series')
for i in range(n):
    print(a,end=" ")
    a,b=b,a+b;
```
Output
```
enter the number of terms:10
fibanacci series
0 1 1 2 3 5 8 13 21 34
```
6. ## find the grosspay using try end except
```
try:
    hours=int(input("enter the number of hours"))
    rate=10
    grosspay=rate*hours
    print('gross salary',grosspay)
except:
    print("please enter the positive numeric value")
```
Output
```
enter the number of hours5
gross salary 50
enter the number of hours1.6
please enter the positive numeric value
```
7. ## by using rate nad working hours find the grosspay
```
hours=int(input("enter the number of hours"))
rate=10
grosspay=rate*hours
print('gross salary',grosspay)
```
Output
```
enter the number of hours24
gross salary 240
```
8. ## To compute the gross pay of the user with min 35 hours and overtime
```
try:
    overtime_pay = 0
    hours = float(input("Enter the number of hours: "))
    rate = 10

    if hours > 35:
        overtime = hours - 35
        overtime_pay = overtime * (rate * 1.5)
        gross_pay = (35 * rate) + overtime_pay
    else:
        gross_pay = hours * rate

    print("The gross pay is:", gross_pay)

except ValueError:
    print("Please enter the hours in numeric value.")
```
Output
```
Enter the number of hours: 45
The gross pay is: 500.0
```

