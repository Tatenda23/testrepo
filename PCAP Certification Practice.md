```python
a=[0]
b=a[:]
a[0]
a[0]=1
```


```python
print(a[0])
```

    1



```python
print(len(a))
```

    1



```python
print(len(b))
```

    1

2 ** 3 ** 2** 1
this is evaluated as 2**1
then 3**2=9
then 2**9=512


```python
print('Peter\'s sister\'s name\'s \"Anna\"')
print("Peter's sister's name's \"Anna\"")
#Invalid Syntax print("Peter's sister's name's "Anna"")
# Invalid Syntax print('Peter's sister's name's "Anna"')
```

    Peter's sister's name's "Anna"
    Peter's sister's name's "Anna"



```python
z, y, x = 2, 1, 0
x, z = z, y
y = y -z
print(x,y,z)
```

    2 0 1



```python
lst = ["A", "B", "C", 2, 4]
del lst[0:-2]
print(lst)
```

    [2, 4]



```python
#print keys only
dict = { 'a': 1, 'b': 2,  'c': 3 }
for item in dict:
    print(item)
```

    a
    b
    c



```python
s = 'python'
for i in range(len(s)):
    i = s[i].upper()
    print(s, end="")
   
```

    pythonpythonpythonpythonpythonpython


```python
s = 'python'
for i in range(len(s)):
    i = s[i].upper()
    print(i, end="")
```

    PYTHON

lst = [[c for c in range(r)] for r in range(3)]
for x in lst:
    for y in x:
        if y < 2:
            print('*', end='')
#output is ***
Explanation of lst = [[c for c in range(r)] for r in range(3)]:
-r takes values 0,1 and 2. This means [c for c in range(r)] is going to produce 3 list
-each produced list will have values when range(r) takes range(0),range(1) and range(2)


```python
lst = [[c for c in range(r)] for r in range(3)]
lst
```




    [[], [0], [0, 1]]




```python
for x in lst:
    for y in x:
        print(y)
```

    0
    0
    1



```python

```
