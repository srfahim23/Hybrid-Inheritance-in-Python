# Hybrid-Inheritance-in-Python

Hybrid inheritance is a combination of multiple inheritance and single inheritance in object-orineted programming. It is a type of inheritance in which multiple inheritance is used to inherit the properties of multiple base classes into a single derived class, and single inheritance is udet to inherit the properties of the derived class into a sub-derived class.

In Python, hybrid inheritance can be implemented by creating a class hierarchy, in whch a base class is inherited by multiple derived classes, and one of the derived class is inheritaed by multiple derived classes, and one of the derived classes is further inherited by a sub-derived class.

# Syntax
The syntax for implementing Hybrid Inheritance in Python is the same as for implementing Single Inheritance, Multiple Inheritance, Of Hierarchical Inheritance.

Here's the syntax for defining a hybrid inheritance class hierarchy:

    class BaseClass1:
        # attributes and methods

    class BaseClass2:
        # attributes and methods

    class DerivedClass(BaseClass1, BaseClass2):
        # attributes and methods
        
                