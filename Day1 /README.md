## basic codes
1. ##
```
x=2 
print(x)
x=x+2
print(x)
```
Output
```
2
4
```
2. ##
```
x=25
if x<10:
    print('hello')
if x>20:
    print('hai')
print('finish')
```
Output
```
hai
finish
```
3. ##
```
n=5
while n>0:
    print(n)
    n=n-1
print('blash off')
```
Output
```
5
4
3
2
1
blash off
```
4. ##
```
nam=input('who are you:\n')
print('welcome',nam)
```
Output
```
who are you:
Sudarshan RS
welcome Sudarshan RS
```
5. ##
```
x=1+2**3/4*5
print(x)
```
Ouptut
```
11.0
```
6. ##
```
astr= 'hello bob'
try:
    istr=int(astr)
except:
    istr=-1
print('first',istr)
```
Output
```
first -1
```
7. ##
```
astr= '123'
try:
    istr=int(astr)
except:
    istr=-1
print('first',istr)
```
Output
```
first 123
```
8. ##
```
astr= '123'
try:
    print('hello')
    istr=int(astr)
    print('world')
except:
    istr=-1
print('first',istr)
```
Output
```
hello
world
first 123
```
9. ##
```
astr= 'bob'
try:
    print('hello')
    istr=int(astr)
    print('world')
except:
    istr=-1
print('first',istr)
```
Output
```
hello
first -1

```


