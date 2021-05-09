
# 1. String Format
## Use string format to fill in blanks with variable
```py
'My nubmer is {} and my name is {}'.format(num, name)
```

## This makes it more flexible

```py
'My nubmer is {a} and my name is {b}'.format(b=num, a=name)
```
 
## Left closed, right open
```py
s[3:6]
```
# 2. Tuple 
1. It is faster than list when iterating 
2. Can be used in Dictionary keys
# 3. Functions
```py
def times2(var):
    return var*2
seq=[1,2,3,4,5]
list(map(times2,seq))
#This will apply times2 to each element of seq

list(filter(lambda num: num%2 ==0, seq))
#This will filter out elements that satisfy the condition given in the function 
```
