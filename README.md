# To the AirBnB clone project, welcome!
---

### First move: Create an interpreter for commands to control your AirBnB objects.
The AirBnB clone is the initial stage towards creating your own complete web application. This first step is crucial since all subsequent projects will make use of the things you produce during this project: Database storage, API access, front-end integration, HTML/CSS templating.

#### Each activity is connected to the next and will aid in:
- Make BaseModel your parent class to handle the initialization, serialization, and deserialization of your future instances.
- Make a straightforward serialization/deserialization flow: Example – Dictionary – a JSON string Create the first abstracted storage engine and all classes used by AirBnB (User, State, City, Place, etc.) that derive from BaseModel.
- Build the project's initial abstracted storage engine: filing cabinets.
generate all unittests to ensure that our classes and storage engine are working properly.

## An interpreter for commands is what?
---
###### Do you still recall the Shell? The only difference is that it is only applicable in one use-case. In our scenario, managing the project's constituent parts is important:

- Make a new item (ex: a new User or a new Place)
- Obtain an object from a database, file, etc.
- rform operations on objects (such as a count, statistics, etc.).
- date an object's characteristics
- Destroy Something 

#### Installation:
---
~~
Step 1: Clone this repository 
Step 2: Switch to the repo's directory 
~~

#### Usage
---

~~ ┌──(Victor_Benson)-[~/Desktop/Software Engineering/ALX School/AirBnB_clone]
└─$ ./console.py
(hbnb) help

Documented commands (type help <topic>):

========================================
EOF all create destroy help quit show update 

(hbnb)
~~

## Learning Objectives 
---
You should be able to explain the following to anyone at the conclusion of this assignment without using Google:

- The best way to make a Python package
- How to use the Python cmd module to construct a command interpreter
- How to do unit testing in a huge project and what it is
- Steps for Deserializing and Serializing a Class
- Creating and reading JSON files
- Managing date and time
- Describe a UUID
- How to utilize *args and what it does
- How to utilize **kwargs and what it is
- How a function should handle named arguments
