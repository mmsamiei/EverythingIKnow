# Singleton

## What is the problem?

The Singleton pattern is used when we want to guarantee that only one instance of a given class exists during runtime.

## What is the solution?

All implementations of the Singleton have these two steps in common:

* Make the default constructor private, to prevent other objects from using the `new` operator with the Singleton class.
* Create a static creation method that acts as a constructor. Under the hood, this method calls the private constructor to create an object and saves it in a static field. All following calls to this method return the cached object.



