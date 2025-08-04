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
10. ##
```
while True:
    line=input('>')
    if line == 'done':
        break
    print(line)
print('done!')
```
Output
```
>hai
hai
>hello im sudarshan
hello im sudarshan
>123
123
>done
done!
```
11. ##
```
while True:
    line=input('>')
    if line[0] == '#':
        continue
    if line == 'done':
        break
    print(line)
print('done!')
```
Output
```
>hai
hai
>hello
hello
>#done
>done
done!
```
12. ##
```
for i in(5,4,3,5,6):
    print(i)
print('done')
```
Output
```
5
4
3
5
6
done
```
13. ## counting of loop
```
count=0
print('before')
for thing in [9,41,12,3,74,15]:
    count =count+1
    print(count,thing)
print('after',count)
```
Output
```
before
1 9
2 41
3 12
4 3
5 74
6 15
after 6
```
14. ## Summing of loop
```
count=0
print('before')
for thing in [9,41,12,3,74,15]:
    count =count+thing
    print(count,thing)
print('after',count)
```
Output
```
before
9 9
50 41
62 12
65 3
139 74
154 15
after 154
```
14. ## finding aveerage in a loop
```
count=0
sum=0
print('before')
for value in [9,41,12,3,74,15]:
    count =count+1
    sum=sum+value
    print(count,sum,value)
print('after',count)
```
Output
```
before
1 9 9
2 50 41
3 62 12
4 65 3
5 139 74
6 154 15
after 6
```




