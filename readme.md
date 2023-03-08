# Fundamental Data types
- [x] int
- [x] float
- [x] complex
- [x] bool
- [x] str
- [x] tuple
- [x] set
- [x] dict

# Classes -> Custom types
# Specialized Data types
# None

---

### int and float
```python
print(3 + 8)
print(type(0.4))
print(type(2 / 4))
print(5 // 4))
print(2 ** 3)
print(5 % 4)

```

---

## MATH FUNCTION
```python
print(round(4.4))
print(abs(-20))
```


## Binary representation
print(bin(3))
to convert it back:
print(int('0b101', 2)

---

### NAMING CONVENTIONS
- start with letters or underscore
- use snake_case
- CONSTANT uses Uppercase
- Dont use dunders i.e __init__

---

### Expression vs statement
```python
iq = 100
user_age = iq / 5

iq/5 is an expression, does something
user_age = iq/5 is a statement i.e holds something
iq=100 is a statement too
```

---

## Augmenteed assignment operator
```python
a = 4
a += 2

print(a)
```


---

## String
```python
username = 'jogn'
password = '1234'
details = '''
i am
a f
ap
'''

print(username)
print(password)
print(details)

username = 'jogn'
password = '1234'
full_name = username + " " + password

print(full_name)
```


---

## Type conversion
```python
print(type(str(100))) // <class, str>
print(type(int(str(100)))) // <class, int>

```

## Escape Sequence
```python
weather = "it's sunny"
weather = 'it\'s sunny'
queston = '\t what is your name? \n'

```

---

## Formatted string
```python
1. The hard way
name = 'Johnny'
age = 56

print("hello your name is " + name + " and your age is" + str(age))

2. proper way
print(f"hello your name is {name} and your age is {age}")

or 

print("hello your name is {} and your age is {}".format(name,age))

or

print("hello your name is {1} and your age is {2}".format(name,age))

or

print("hello your name is {new_name} and your age is {new_age}".format(new_name='saly',new_age=8))

```
---

## String index
```python
name='me me me'

print(name[0])
print(len(name))

[start:stop:stepover]  the default stepover is 1
print(name[1:3])

name = '0123456789'

print(name[0:9:2])

name = '0123456789'

print(name[0:9:2])
print(name[:4])
print(name[2:])
print(name[::1])
print(name[-1])


Reverse: print(name[::-1])

```

---

## Immutability
```python
selfish = '09987654567'

selfish[0] = 6
print(selfish) // throws error, bcos you cant reassign part of a string


```
---

## bool
```python
is_tall = True
print(is_tall)
print(bool(0))
print(bool(1))
print(bool('True'))
print(bool('False'))
```


---

## INPUT
```python
your_age=input("type your age here: \n")
print(f"you are {your_age} years old")

Exercise 2
birth_year = input('what year were you born?\n')

age = 2023 - int(birth_year)
print("\n")
print(f"you are {age} years old")

```


---

## Password Exercise
```python
username = input("please enter your username\n")
password = input("please enter your password\n")

password_lenght = len(password)
password_to_star = password_lenght * '*'

result  = f"Dear {username} your password {password_to_star} is {password_lenght} char long"

print(result)
```

---


## List
```python
Array slicing
# Fundamental Data types
int
float
# complex
bool
str
tuple
set
dict
```

# Classes -> Custom types
# Specialized Data types
# None

---

## int and float
```python
print(3 + 8)
print(type(0.4))
print(type(2 / 4))
print(5 // 4))
print(2 ** 3)
print(5 % 4)

```

---

## MATH FUNCTION
```python
print(round(4.4))
print(abs(-20))

```

---

# Binary representation
```python
print(bin(3))
to convert it back:
print(int('0b101', 2)

```

---

### NAMING CONVENTIONS
```python
- start with letters or underscore
- use snake_case
- CONSTANT uses Uppercase
- Dont use dunders i.e __init__

```

## Expression vs statement
```python
iq = 100
user_age = iq / 5

iq/5 is an expression, does something
user_age = iq/5 is a statement i.e holds something
iq=100 is a statement too
```

---

## augmenteed assignment operator
```python
a = 4
a += 2

print(a)
```


---

## String
```python
username = 'jogn'
password = '1234'
details = '''
i am
a f
ap
'''

print(username)
print(password)
print(details)

username = 'jogn'
password = '1234'
full_name = username + " " + password

print(full_name)
```


---

## Type conversion
```python
print(type(str(100))) // <class, str>
print(type(int(str(100)))) // <class, int>
```


#### Escape Sequence
```python
weather = "it's sunny"
weather = 'it\'s sunny'
queston = '\t what is your name? \n'
```


---

#### Formatted string
```python
1. The hard way
name = 'Johnny'
age = 56

print("hello your name is " + name + " and your age is" + str(age))

2. proper way
print(f"hello your name is {name} and your age is {age}")

or 

print("hello your name is {} and your age is {}".format(name,age))

or

print("hello your name is {1} and your age is {2}".format(name,age))

or

print("hello your name is {new_name} and your age is {new_age}".format(new_name='saly',new_age=8))

```
---

#### String index
```python
name='me me me'

print(name[0])
print(len(name))

[start:stop:stepover]  the default stepover is 1
print(name[1:3])

name = '0123456789'

print(name[0:9:2])

name = '0123456789'

print(name[0:9:2])
print(name[:4])
print(name[2:])
print(name[::1])
print(name[-1])


Reverse: print(name[::-1])
```


---

## Immutability
```python
selfish = '09987654567'

selfish[0] = 6
print(selfish) // throws error, bcos you cant reassign part of a string

```

---

## bool
is_tall = True
```python
print(is_tall)
print(bool(0))
print(bool(1))
print(bool('True'))
print(bool('False'))

```

---

## INPUT
```python
your_age=input("type your age here: \n")
print(f"you are {your_age} years old")

Exercise 2
birth_year = input('what year were you born?\n')

age = 2023 - int(birth_year)
print("\n")
print(f"you are {age} years old")
```



---

## Password Exercise
```python
username = input("please enter your username\n")
password = input("please enter your password\n")

password_lenght = len(password)
password_to_star = password_lenght * '*'

result  = f"Dear {username} your password {password_to_star} is {password_lenght} char long"

print(result)
```



## List
```python
List slicing
basket = ["orange", "pawpaw", "pineapple"]

print(basket[0:1])
print(basket[0:1:1])



Strings are immutable i.e you cannot reassign strings toanother varibale
List(array) are mutable
basket = ["orange", "pawpaw", "pineapple"]

print(basket[0:1])
```



---

## Matrix
```python
matrix = [
  [1,0,3],
  [0,1,0],
  [1,0,1]
]

print(matrix[0][2])

```

---

## List methods
```python
basket  = [1,2,3,4,5,6]
```

### adding
basket.append(10)
new_list = basket
print(new_list)


#### insert
basket  = [1,2,3,4,5,6]

### inser
basket.insert(3,100)
new_list = basket
print(new_list)


## eXtend
basket  = [1,2,3,4,5,6]

basket.extend([3,100])
new_list = basket
print(new_list)


### pop
basket  = [1,2,3,4,5,6]
basket.pop() // last element
basket.pop(0) //removes the index
print(basket)


#### remove
 basket  = [1,2,3,4,5,6]
basket.remove(2) #removes the value and not the index 
print(basket)


### clear
basket  = [1,2,3,4,5,6]
basket.clear()
print(basket)


### index
basket  = ["a", "b","c","d","e"]

print(basket.index('b'))
print(basket.index('d', 0,4))


#### in
basket  = ["a", "b","c","d","e"]

print("c" in basket)



---

#### count
basket  = ["a", "b","c","d","e"]

print(basket.count('i'))
print(basket.count('a'))


---

## sort
```python
basket  = ["a", "x", "b","c","d","e"]

# print(basket.sort()) // None
basket.sort()
print(basket)


print(sorted(basket))


---

### sort and reverse
basket  = ["a", "x", "b","c","d","e"]

## print(basket.sort()) // None
basket.sort()
basket.reverse()
print(basket)
```


## range with list
```python
print(list(range(1,50)))
print(range(100))
```


---

## Join
```python
sentence = " "

new_sentence = sentence.join(["my", "name", "is", "jojo"])
print(new_sentence)
```



---


## list unpacking
```python
basket = [1,2,3]

a,b,c = [1,2,3]

print(a)
print(c)
print(b)


Example2
basket = [1,2,3]

a,b,c, *other = [1,2,3,4,5,6,7,8,9]

print(a)
print(c)
print(b)
print(other)


Example 3
basket = [1,2,3]

a,b,c, *other,d = [1,2,3,4,5,6,7,8,9]

print(a)
print(c)
print(b)
print(other)
print(d)
```


---

## None === null



---

## Dictionary
```python
dictionary = {
  'a':1,
  'b':2
}

# print(dictionary['2'])
print(dictionary)


Example 2
dictionary = {
  'a':[1,2,3],
  'b':True,
  'c':'hello'
}
```

## print(dictionary['2'])
```python
print(dictionary)
print(dictionary['a'][2])
```


## Handling errors in dictionary
```python
dictionary = {
  'a':[1,2,3],
  'b':True,
  'c':'hello'
}

print(dictionary.get('age')) // None

```

---

## Create dictionary method 2
```python
user = dict(name="joe")
print(user)

```

---


## Dict items
```python
users = {
  'a':'mimi',
  'b':'timi'
}

print(users.items())
print(users.keys())
print(users.values())

```

---


#### dict.clear()
print(users.clear())


---

## Copy in dict
```python
users = {
  'a':'mimi',
  'b':'timi'
}

users2 = users.copy()
print(users2)

```

---

## pop
```python
users = {
  'a':'mimi',
  'b':'timi'
}


users.pop('a')

print(users)
```



---

## update
```python
users = {
  'a':'mimi',
  'b':'timi'
}


print(users.update({'b': 'tope'}))
print(users)
```

---

## Tuple
```python
they are immutable

my_tuple = (1,2,3,4,5)
print(my_tuple[0])
print(1 in my_tuple)
```


---

## set
```python
there is no duplicate in set
my_set = {1,2,3,4,5,6,5,6}
my_set.add(100)
my_set.add(2)
print(my_set)
print(list(my_set))

Example 2
my_list = [1,2,3,4,2,2,3]
print(set(my_list))

only returns unique items, no duplicate
```


---

## set difference
```python
my_set = {1,2,3,4,5,6,5,6}
your_set = {4,5,6,7,8}
print(my_set.difference(your_set))


#### Example 2
my_set = {1,2,3,4,5,6,5,6}
your_set = {4,5,6,7,8}
# print(my_set.discard(5))
# print(my_set)

# print(my_set.difference_update(your_set))
# print(my_set)


#  intersection
# print(my_set.intersection(your_set))
# print(my_set)

# union
# print(my_set.union(your_set))
# print(my_set | your_set)

# print(my_set.issubset(your_set))

# print(my_set.issuperset(your_set))
# print(your_set.issuperset(my_set))
```


---

## conditions
```python
is_old= False
is_licensed = True

if is_old:
  print("you are old")
elif is_licensed:
  print('you are licenced')
else:
  print("you are young")

print("hello")
```


---

## truthy or falsy


```python
name = bool("james")
number1 = bool(1)
number2 = bool(0.0)
number3 = bool(0.0)
print(name)
print(number1)
print(number2)


Exercise
username="john"
password="1234"

if not username and password:
  print("logged in")
else:
  print("try again")

```
---

## ternary
```python
is_friend  = True
can_message ="hey there" if is_friend else "not fiend"

print(can_message)
```



## Short circuting
```python
is_Friend = True
is_user = False

if is_Friend or is_user:
    print("hello")

it means once one is statement return a Truthy value dont waste time evaluating the rest

```
---

## comparison operator
```python
print(not(False))
print(not(1== 1))
print(1<2)

```

---


## Equality

```python
# double equality
print(1 == int('1'))

#
print('1' is 1)    #false    
```        


---


## Loops

```python
# an iterable is the collection here
collection = 'bayomi'
for item in collection:
  print(item)


# iterating a list
for a in [1,2,3,4,5]:
  print(a)

# iterating a set
for b in {1,2,3,4,5}:
  print(b)

# iterating a tuple
for c in (1,2,3,4):
  print(c)

```


---


## iterating over dictionaries

```python
user= {
  'name':'Golem',
  'age':90
}

for x in user.items():
  print(x)

print("==============")


for b in user:
  print(b)

print("==============")

for b in user.values():
  print(b)


print("==============")
for b in user.keys():
  print(b)

print("==============")
for key,value in user.items():
  print(f"key is : {key} and value is: {value}")
```


---

## Exercise
```python
counter  = 0
my_list = [1,2,3,4,5,6,7,8,9,10,11,12]

for item in my_list:
  counter = counter + item

print(counter)
```

---


## range
```python
print(range(1,10))

for number in range(1,20):
  print(number)

Exercise 2
for _ in range(0,10,2):
  print(_)

Exercise 3
for _ in range(4):
  print(list(range(10)))

```

---

## ENUMERATE
```python
for i, char in enumerate('hello'):
  print(i, char)

print("=======================\n")

for i, char in enumerate([1,2,3,4,5]):
  print(i, char)

```

---


## While loop
```python
i = 0

while i < 10:
  print(i)
  i += 1
else:
  print("we are done")


```
---


## Break, continue, pass

```python
for item in [1,2,3,4,5,6]:
  if(item == 3):
    continue
  print(item)

print("=======================")

for item in [1,2,3,4,5,6]:
  if(item == 3):
    break
  print(item)

print("=======================")

for item in [1,2,3,4,5,6]:
  if(item == 3):
    pass # for handle pseudo code
  print(item)
print("=======================")

```

---

## function
```python
def greet():
  print("saying hello")

greet()

#### parameter

# positional parameters
def greet(name):
  print(f"hello: {name}")

# positional arguments
greet("tayo 🎉🎉🎉🎉🎉")
greet("timi") 


```
---


## Default paramters and keywords
```python
# positional parameters
def greet(name,emoji):
  print(f"hello: {name}, {emoji}")


# key word argument
greet(emoji="🚀🚀🚀", name="bibi")


```
---

### default parameters

```python
# default parameters
def greet(name="bib",emoji="🙄🙄🙄"):
  print(f"hello: {name}, {emoji}")


# key word argument
greet()
```



---

### Return statement

```python
def sum(num1, num2):
  return num1 + num2

print(sum(4,4))
```