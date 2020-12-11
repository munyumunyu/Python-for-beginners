### Strings in  Python
* Strings in python can be in either double quotes or single quotes
```Python
my_str = 'Hello World'
string = "Hello"
```

#### String Concatenation
* We Concatenate strings using **+** operator 
```Python
str1 = 'Hello'
str2 = 'World'
print(str1+" " +str2)
#This will print out Hello World
```
* You cannot concatenate strings with integers

```Python
8 + 'hello'
# This will give an error
but we can do this using an str() function and it will convert the the int into str then you can concatenate
```

* You can also use the **+=** operator to concatenate strings

```Python
string = "Cat"
string += " Dogs"
print(string)
#This will print out Cat Dogs
```

#### Formatting Strings
There's a new method to interpolate the strings 
* The method is called the F-strings this will help you convert the int value into a string 
```Python
x = 10
print(f"I have told you  {x}  times to clean the floor correctly")
# This will print I have told you 10 times to clean the floor correctly
# This a new way of interpolating string 
y = 'I have told you {} times to clean the floor correctly'.format(x)
# This an old way of doing it and its applicable in **python 2.7**
```

#### String Index
```Python3
x = "Hello"
print(x[0])
#This will print out H 
# [] We use this for index
# This is useful for lists
```

#### Converting DataTypes
* We use built-in functions to convert the data types.
* For example int() str() float() 
* int () this is a built-in function that is used to convert a number into an integer.
* float() This is used to convert the number into a float
* str() This is used to convert to a string
**Note: We used input() function to get the user input**
```Python3
x = input('What is your age') #this will prompt to the user
print(x) # whatever user types it will be printed out
```
