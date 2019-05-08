

```python
print("hello world")
```

    hello world
    


```python
var1=123
var2=var1**var1
var3=var1*var2
print(len(str(var2)))
```

    258
    


```python
### string sclicing
```


```python
str1="python programing"
str1[0]
str1[len(str1)-1]
str1[:6]
```




    'python'




```python
str1[len(str1)-1::-1]
```




    'gnimargorp nohtyp'




```python
print((str1[:6]+ "\n")*3)
```

    python
    python
    python
    
    


```python
###  Lists
```


```python
li=[123,345,'python']
len(li)
li[2]
li[len(li)-1]='programming'
li.append('python')
print(li)
li[:2]
li.insert(0,123)
li.pop(2)
li.pop(3)
li2=[[1,2,3],[4,5,6],[7,8,9]]
li2[1][0]
li2.insert (3,[10,11,12])
```

    [123, 345, 'programming', 'python']
    


```python
li.pop(0)
```




    123




```python
#print(li)
```


```python
li.insert(0,123)
```


```python
li2=[[1,2,3],[4,5,6],[7,8,9]]
li2[1][0]

```




    4




```python
print(li2)
```

    [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
    


```python
li2.insert(3,[10,11,12])
```


```python
print(li2)
```

    [[1, 2, 3], [4, 5, 6], [7, 8, 9], [10, 11, 12]]
    


```python
li2.pop(3)
```




    [10, 11, 12]




```python
for i in range(0,len(li2)):
    for j in range(0,len(li2)[i]):
        print(li2[i][j],end=" ")
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-41-6fcd0b5b2c8c> in <module>
          1 for i in range(0,len(li2)):
    ----> 2     for j in range(0,len(li2)[i]):
          3         print(li2[i][j],end=" ")
    

    TypeError: 'int' object is not subscriptable



```python
### Tuples
t1=(123,345,567)
t1[2]+t1[1]
t1[len(t1)-1]
```




    567




```python
t1[1:3]
```




    (345, 567)




```python
t1=(123,345,567)
str(t1(0))
```

## Reading input from  the user


```python
str1=input()

str1
```

    python
    




    'python'



## Dictionaries


```python
d1= {'procedural':'c','scripting':'python','functional':'haskell'}
```


```python
d1.values()
```




    dict_values(['c', 'python', 'haskel'])




```python
d1.keys()
```




    dict_keys(['procedural', 'scripting', 'functional'])




```python
d2={'Symbolic':'Mathematica','Logic':'Prolog'}
d1.update(d2)        ### Merging two dictionaries
```


```python
print(d1)
```

    {'procedural': 'c', 'scripting': 'python', 'functional': 'haskel', 'Symbolic': 'Mathematica', 'Logic': 'Prolog'}
    


```python
d1['Object oriented']='Java'
d1
```




    {'procedural': 'c',
     'scripting': 'python',
     'functional': 'haskel',
     'Symbolic': 'Mathematica',
     'Logic': 'Prolog',
     'Object oriented': 'Java'}




```python

```
