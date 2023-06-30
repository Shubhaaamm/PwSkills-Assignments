Q1. Create one variable containing following type of data:
(i) string
(ii) list
(iii) float
(iv) tuple


```python
# (i) string
onevar = "Hi, I am Shubham"

# (ii) list
onevar = [1, 2, 3, 4, 5]

# (iii) float
onevar = 3.14159

# (iv) tuple
onevar = (6, 7, 8, 9, 10)
```

Q2. Given are some following variables containing data:
(i) var1 = ‘ ‘
(ii) var2 = ‘[ DS , ML , Python]’
(iii) var3 = [ ‘DS’ , ’ML’ , ‘Python’ ]
(iv) var4 = 1.


```python
var1 = ''
var2 = '[ DS , ML , Python]'
var3 = [ 'DS' , 'ML' , 'Python' ]
var4 = 1.
print(type(var1))
print(type(var2))
print(type(var3))
print(type(var4))
```

    <class 'str'>
    <class 'str'>
    <class 'list'>
    <class 'float'>


Q3. Explain the use of the following operators using an example:
(i) /
(ii) %
(iii) //
(iv) **


```python
a=10
b=5
print(a/b)
print(a%b)
print(a//b)
print(a**b)
```

    2.0
    0
    2
    100000


Q4. Create a list of length 10 of your choice containing multiple types of data. Using for loop print the
element and its data type.


```python
my_list = [1, 'Hello', 3.14, True, [1, 2, 3], {'name': 'John', 'age': 25}, (4, 5, 6), None, False, 'World']
for i in my_list:
    print(type(i))
```

    <class 'int'>
    <class 'str'>
    <class 'float'>
    <class 'bool'>
    <class 'list'>
    <class 'dict'>
    <class 'tuple'>
    <class 'NoneType'>
    <class 'bool'>
    <class 'str'>



```python
Q5. Using a while loop, verify if the number A is purely divisible by number B and if so then how many
times it can be divisible.
```


```python
A=20
B=5
if A%B==0:
    count=A//B
    print("number A is divisible by B :")
    print(count)
else:
    print("not divisible by B")
```

    number A is divisible by B :
    4


Q6. Create a list containing 25 int type data. Using for loop and if-else condition print if the element is
divisible by 3 or not.


```python
data=[8, 15, 12, 9, 17, 6, 21, 10, 27, 14, 19, 3, 5, 30, 11, 22, 18, 7, 25, 13, 4, 16, 23, 20, 2]

for num in data:
    if(num % 3==0):
        print("num is divisible by 3 ")
    else:
        print("num is not divisible")
```

    num is not divisible
    num is divisible by 3 
    num is divisible by 3 
    num is divisible by 3 
    num is not divisible
    num is divisible by 3 
    num is divisible by 3 
    num is not divisible
    num is divisible by 3 
    num is not divisible
    num is not divisible
    num is divisible by 3 
    num is not divisible
    num is divisible by 3 
    num is not divisible
    num is not divisible
    num is divisible by 3 
    num is not divisible
    num is not divisible
    num is not divisible
    num is not divisible
    num is not divisible
    num is not divisible
    num is not divisible
    num is not divisible


Q7. What do you understand about mutable and immutable data types? Give examples for both showing
this property.


```python
# Mutable Datatypes:
#1. Mutable data types are those whose values can be modified after they are assigned.
#2. Operations performed on a mutable object can change its internal state.
# example: List
list1 = [1, 2, 3]
list2 = list1

list1.append(4)

print(list1)  
print(list2)  

#---------------------------------------------------------------------
# Immutable Datatypes:
# 1.Immutable data types are those whose values cannot be modified once they are assigned.
# 2.Any operation on an immutable object creates a new object rather than modifying the existing one.
#example: String
string1 = "Hello"
string2 = string1

string1 += " World"

print(string1)  
print(string2)  


```

    [1, 2, 3, 4]
    [1, 2, 3, 4]
    Hello World
    Hello



```python

```
