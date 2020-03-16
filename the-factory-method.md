# The factory method

## What's Problem?

The problem is for the case that when client asks for an object but doesn't want to involve itself in creating it and to know where the object is coming from. Consider example that you go to a ‌bakery which has two type bread, A and B. you only say to the baker the name of bread and don't involve yourself in creating it. Then Baker hear your request and according to name which is said in your request, bake that bread and then submit it to you. 

In Factory method, we write a single method to handle object creation. 

## A Symbolic Example

```python
class Apple:
    pass

class Orange:
    pass

def function(name):
    dictionary = {'apple':Apple, 'orange':Orange}
    SelectedClass = dictionary[name]
    return SelectedClass()
```



