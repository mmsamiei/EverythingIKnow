# \*args and \*\*kwargs in Python

## \*args

The special syntax _\*args_ in function definitions in python is used to pass a variable number of arguments to a function. It is used to pass a non-keyworded, variable-length argument list.

_What \*args allows you to do is take in more arguments than the number of formal arguments that you previously defined. With \*args, any number of extra arguments can be tacked on to your current formal parameters \(including zero extra arguments\)._

For example : we want to make a multiply function that takes any number of arguments and able to multiply them all together. It can be done using \*args.

Using the _, the variable that we associate with the_  becomes an iterable meaning you can do things like iterate over it, run some higher order functions such as map and filter, etc.

```python
def multiply(a, b, *argv):
    sum = a * b
    for arg in argv:
        sum *= arg
    return sum

print(multiply(3,6))
print(multiply(3,6,2))
print(multiply(3,6,2,-1))
```

output will be:

```text
18
36
-36
```

## **\*\*kwargs**

The special syntax _\*\*kwargs_ in function definitions in python is used **to pass a keyworded, variable-length argument list**. **We use the name** _**kwargs**_ **with the double star. The reason is because the double star allows us to pass through keyword arguments** \(and any number of them\).

A keyword argument is where you provide a name to the variable as you pass it into the function.

```python
def myFun(**kwargs):
    for key, value in kwargs.items():
        print("{} == {}".format(key, value))


myFun(friend='Danial', Enemy='Trump', Teacher='Habibi')
```

output will be:

```text
friend == Danial
Enemy == Trump
Teacher == Habibi
```

## How to call function with \*args and \*kwargs pretty?  :\)

```python
arg = (2, 11, "banana")
kwargs = {"friend": "Danial", "Enemy":"Trump", "Age": 22}
f(*arg, **kwargs)
```

