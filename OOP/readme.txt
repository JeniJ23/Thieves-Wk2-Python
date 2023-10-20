1. OOP (Object Oriented Programming)
- Programming paradigm that relies on the concept of classes and objects.
- In other words, it is a way to structure your code in a efficient way

-------------------------------------------------------------------------
Basic OOP Example:
class Student():
    
    (constructor)
    def __init__(self, name):
        (attributes)
        self.name = name
    
    (methods)
    def greet(self):
        return f'Hello my name is {self.name}'

(Instance of the Student Class)
christian = Student('christian')

(Accessing methods inside of the Instance)
christian.greet()
---------------------------------------------------------------------------

2. 4 Pillars of OOP
-- Encapsulation: Binding of data and functions (attributes and methods)
-- Abstraction: Abtracting away irrelevant information (Ex: len() function)
-- Inheritance: Allows new objects to inherit properties from existing/parent objects
-- Polymorphism: Single entity in a programming language that can behave in multiple ways depending on the context (Ex: '+' operator)

3. super()
--  Gives access to methods and properties of a parent or sibling class.