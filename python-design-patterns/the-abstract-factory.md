# The abstract factory

## What is the abstract factory?

The **Abstract Factory** pattern looks like the factory objects we’ve seen previously, with not one but several factory methods. Each of the factory methods creates a different kind of object.

## What's the problem?

consider you go to a resturant which has fruits and beverages \(don't fuss me! :\)\). and you want to order one fruit with one drink. a way to implement it in python is to have a factory method which has many many if and else in order to check which combination you order. but there is a better way and that is implementing two factory methods inside a class that each of them determine a level of your preference \(one for fruit and another for drink\).

## A sample code

```python
class Apple():
    def __init__(self):
        self.flavor = 'sweet'
        self.price = 2

class Orange():
    def __init__(self):
        self.flavor = 'sour'
        self.price = 3

class Cucumber():
    def __init__(self):
        self.flavor = 'watery'
        self.price = 0.5

def Cola():
    def __init__(self):
        self.price = 10
        
def Milk:
    def __init__(self):
        self.price = 5

def Water:
    def __init__(self):
        self.price = 1
    

class Order:
    def __init__(self):
        
```

##  



