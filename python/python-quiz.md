Python Assessment
-------------------

#### Q1. What is an abstract class?
- An abstract class is the name for any class from which you can instantiate an object.
- Abstract classes must be redefined any time an object is instantiated from them 
- Abstract classes must inherit from concrete classes.
- An abstract class exists only so that other "concrete" classes can inherit from the abstract class.

#### Q2. What happens when you use the build-in function "any()" on a list?
- The "any()" function will randomly return any item from the list.
- The "any()" function returns True if any item in the list evaluates to True. Otherwise, it returns Fals. // CORRECT
- The "any()" function takes as arguments the list to check inside, and the item to check for. If "any" of the items in the list match the item to check for, the function returns True.
- The "any()" function returns a Boolean value that answers the question "Are there any items in this list?"

#### Q3. What data structure does a binary tree degenerate to if it isn't balanced properly?
- linked list
- queue
- set 
- OrderedDict

#### Q4. What is a static method?
- Static methods are called static because they always return "None".
- Static methods can be bound to either a class or an instance of a class.
- They serve mostly as utility methods or helper methods, since they can't access or modify a class's state. //CORRECT
- Static methods can access and modify the state of a class or an instance of a class. 

#### Q5. What are attributes?
- Attributes are long-form version of an "if/else" statement, used when testing for equality between objects.
- Attributes are a way to hold data or describe a state for a class or an instance of a class.
- Attributes are strings that describe characteristics of a class.
- Function arguments are called "attributes" in the context of class methods and instance methods. //CORRECT

#### Q6. What is the term to describe this code?
```javascript
count, fruit, price = (2, 'apple', 3.5)
```
- tuple assignment //CORRECT
- tuple unpacking
- tuple matching
- tuple duplication

#### Q7. What built-in list method would you use to remove items from a list?
- `".delete()" method`
- `pop(my_list)`
- `del(my_list)`
- `".pop()" method`  //CORRECT

#### Q8. What is one of the most common use of Python's sys library?
- to capture command-line arguments given at a file's runtime  //CORRECT
- to connect varios systems, such as connecting a web front end, an API service, a database, and a mobile app
- to take a snapshot of all the packages and libraries in your virtual environment
- to scan the health of your Python ecosystem while inside a virtual environment

#### Q9. What is the runtime of accessing a value in a dictionary by using its key?
- "O(n)", also called linear time
- "O(log n)", also called logarithmic time
- "O(n^2)", also called quadratic time
- "O(1)", also called constant time  //CORRECT

#### Q10. What is the correct syntax for defining a class called Game?
- `class Game: pass`
- `def Game(): pass`
- `def Game: pass`
- `class Game(): pass`

#### Q11. What is the correct way to write a doctest?
- 
```
def sum(a, b):
    """
    sum(4, 3)
    7   
    
    sum(-4, 5)
    1
    """
    return a + b
```
- 
```
def sum(a, b):   //CORRECT
    """
    >>> sum(4, 3)
    7   
    
    >>> sum(-4, 5)
    1
    """
    return a + b
```
- 
```
def sum(a, b):
    """
    # >>> sum(4, 3)
    # 7   
    
    # >>> sum(-4, 5)
    # 1
    """
    return a + b
```
- 
```
def sum(a, b):
    ###
    >>> sum(4, 3)
    7   
    
    >>> sum(-4, 5)
    1
    ###
    return a + b
```


#### Q12. What buit-in Python data type is commonly used to represent a stack?
- set
- list 
- None. You can only build a stack from scratch.
- dictionary

#### Q13. What would this expression return?
```
college_years = ['Freshman', 'Sophomore', 'Junior', 'Senior']
return list(enumerate(college_years, 2019)
```
- `[('Freshman', 2019), ('Sophomore', 2020), ('Junior', 2021), ('Senior', 2022)]`
- `[(2019, 2020, 2021, 2022), ('Freshman', 'Sophomore', 'Junior', 'Senior')]`
- `[('Freshman', 'Sophomore', 'Junior', 'Senior'), (2019, 2020, 2021, 2022)]`
- `[(2019, 'Freshman'), (2020, 'Sophomore'), (2021, 'Junior'), (2022, 'Senior')]`

#### Q14. How does "defaultdict" work?
- "defaultdict" will automatically create a dictionary for you that has keys which are the integers 0-10
- "defaultdict" forces a dictionary to only accept keys that are of the types specified when you created the "defaultdict" (such as string or integers). //CORRECT
- If you try to access a key in a dictionary that doesn't exist, "defaultdict" will create a new key for you instead of throwing a "KeyError".
- "defaultdict" stores a copy of a dictionary in memory that you can default to if the original gets unintentionally modified.

#### Q15. What is the correct syntax for defining a class called "Game", if it inherits from a parent class called "LogicGame"?
- `class Game.LogicGame(): pass`
- `def Game(LogicGame): pass`
- `class Game(LogicGame): pass`
- `def Game.LogicGame(): pass`

#### Q16. What is the purpose of the "self" keyword when defining or calling instance methods?
- `self means that no other arguments are required to be passed into the method`
- `There is no real purpose for the self method; it"s just historic computer science jargona that Python keeps to stay consistent with other programming languages`
- `self  refers to the instance whose method was called` // CORRECT
- `self refers to the class that was inherited from to create the object using self`


#### Q17. Which of these is NOT a characteristic of namedtuples?
- `You can assign a name to each of the namedtuple members and refer to them that way, similarly to how you would access keys in dictionary` //CORRECT
- `Each member of a namedtuple object can be indexed to directly, just like in a regular tuple`
- `namedtuples are just as memory efficient as regular tuples`
- `No import is needed to use namedtuples because they are available in the standard library`

#### Q18. What is an instance method?
- `Instance methods can modify the state of an instance or the state of its parent class` //CORRECT
- `Instance methods hold data related to the instance`
- `An instance method is any class method that doesn"t take any arguments`
- `An instance method is a regular function that belongs to a class, but it must return None`

#### Q19. Which choice is the most syntactically correct example of the conditional branching?
```
num_people = 5

if num_people > 10;
    print("There is a lot of people in the pool.")
elif num_people > 4;
    print("There are some people in the pool.")
elif num_people > 0;
    print("There are a few people in the pool.")
else:
    print("There is no one in the pool.")


    -------------

num_people = 5

if num_people > 10;
    print("There is a lot of people in the pool.")
if num_people > 4;
    print("There are some people in the pool.")
if num_people > 0;
    print("There are a few people in the pool.")
else:
    print("There is no one in the pool.")

    -------------
num_people = 5                            //CORRECT

if num_people > 10;
    print("There is a lot of people in the pool.")
elif num_people > 4;
    print("There are some people in the pool.")
elif num_people > 0;
    print("There are a few people in the pool.")
else:
    print("There is no one in the pool.")
    -------------
    
if num_people > 10;
    print("There is a lot of people in the pool.")
if num_people > 4;
    print("There are some people in the pool.")
if num_people > 0;
    print("There are a few people in the pool.")
else:
    print("There is no one in the pool.")


```
#### Q20. Which statement does NOT describe the object-oriented programming concenpt of encapsulation?
- `It protects the data from outside interference `
- `A parent class is encapuslated and no data from the parent class passes on to the child class`
- `It keeps data and the methods that can manipulate that data in one place`
- `It only allows the data to be changed by methods` //CORRECT


#### Q21.What is the purpose of an if/else statement?

- `An if/else statement tells the computer which chunk of code to run if the instructions you coded are incorrect `
- `An if/else statement runs one chunk of code if all the imports were succesful, and another chunk of code if the imports were not succesful `
- `An if/else statement  executes one chunk of code if a condition it true, but a different chunk of code if the condition is false` //CORRECT
- `An if/else statement tells the computer which chunk of code to run if the is enough memory to handle it. and which chunk of code to run if there is not enough memory to handle it`