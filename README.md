# AirBnB_clone
========================================
##### Group project Python OOP

## Background Context
Welcome to the AirBnB clone project!
Before starting, please read the AirBnB concept page.

__The first step is writing a command interpreter to manage your AirBnB objects.__
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

* put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
* create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
* create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
* create the first abstracted storage engine of the project: File storage.
* create all unittests to validate all our classes and storage engine

__What’s a command interpreter?__
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object


### Concepts & Resources
For this project, we expect you to look at these concepts:

1. Python packages
2. AirBnB clone

Also read or watch:

1. cmd module
2. cmd module in depth
3. packages concept page
4. uuid module
5. datetime
6. unittest module
7. args/kwargs
8. Python test cheatsheet
9. cmd module wiki page
10. python unittest

### General Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

* How to create a Python package
* How to create a command interpreter in Python using the cmd module
* What is Unit testing and how to implement it in a large project
* How to serialize and deserialize a Class
* How to write and read a JSON file
* How to manage datetime
* What is an UUID
* What is *args and how to use it
* What is **kwargs and how to use it
* How to handle named arguments in a function


## Requirements

### Python Scripts
1. Allowed editors: vi, vim, emacs
2. All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
3. All your files should end with a new line
4. The first line of all your files should be exactly #!/usr/bin/python3
5. A README.md file, at the root of the folder of the project, is mandatory
6. Your code should use the pycodestyle (version 2.8.*)
7. All your files must be executable
8. The length of your files will be tested using __wc__
9. All your modules should have a documentation __(python3 -c 'print(__import__("my_module").__doc__)')__
10. All your classes should have a documentation __(python3 -c 'print(__import__("my_module").MyClass.__doc__)')__
11. All your functions (inside and outside a class) should have a documentation __(python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')__
12. A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)


### Python Unit Tests
1. Allowed editors: vi, vim, emacs
2. ll your files should end with a new line
3. All your test files should be inside a folder tests
4. You have to use the unittest module
5. All your test files should be python files (extension: .py)
6. All your test files and folders should start by test_
7. Your file organization in the tests folder should be the same as your project
8. e.g., For models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
9. e.g., For models/user.py, unit tests must be in: tests/test_models/test_user.py
10. All your tests should be executed by using this command: python3 -m unittest discover tests
11. You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
12. All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
13. All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
14. All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
15. We strongly encourage you to work together on test cases, so that you don’t miss any edge case


#### GitHub
There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.

All tests should also pass in non-interactive mode: $ echo "python3 -m unittest discover tests" | bash

### Copyright - Plagiarism
* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.


By 
  * Benedict Igbukolu
  * Daniel Izevbije






