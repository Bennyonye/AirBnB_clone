## AirBnB Clone Console

### Table of Contents

* [Introduction](#introduction)
* [Environment](#environment)
* [Installation](#installation)
* [Testing](#testing)
* [Usage](#usage)
* [Authors](#authors)

### Introduction

This project aims to build a clone of [AirBnB](https://www.airbnb.com/). The console serves as a command interpreter for managing object abstraction and storage. For more information, refer to the [Wiki](https://github.com/ralexrivero/AirBnB_clone/wiki).

Tasks performed by the console include:

* Creating a new object
* Retrieving an object from a file
* Performing operations on objects
* Destroying an object

#### Storage

All classes are managed by the `Storage` engine within the `FileStorage` class.

### Environment

* [Ubuntu](https://ubuntu.com/)
* [GNU Bash](https://www.gnu.org/software/bash/)
* [Python](https://www.python.org)
* [Vim](https://www.vim.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com)

Style guidelines:

* [pycodestyle (version 2.7.*)](https://pypi.org/project/pycodestyle/)
* [PEP8](https://pep8.org/)

Development and testing were conducted on Ubuntu 20.04 LTS using Python 3.8.3. Editors used include Vim 8.1.2269, VSCode 1.6.1, and Atom 1.58.0. Version control was managed using Git 2.25.1.

### Installation

```bash
git clone https://github.com/aysuarex/AirBnB_clone.git
```

Navigate to the `AirBnb` directory and execute:

```bash
./console.py
```

#### Execution

In interactive mode:

```bash
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

In Non-interactive mode:

```bash
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

### Testing

All tests are defined in the `tests` folder.

#### Documentation

* Modules:

```python
python3 -c 'print(__import__("my_module").__doc__)'
```

* Classes:

```python
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
```

* Functions (inside and outside a class):

```python
python3 -c 'print(__import__("my_module").my_function.__doc__)'
```

and

```python
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
```

#### Python Unit Tests

* unittest module
* File extension `.py`
* Files and folders start with `test_`
* Organization: for `models/base.py`, unit tests in: `tests/test_models/test_base.py`
* Execution command: `python3 -m unittest discover tests`
* or: `python3 -m unittest tests/test_models/test_base.py`

#### Run tests in interactive mode

```bash
echo "python3 -m unittest discover tests" | bash
```

#### Run tests in non-interactive mode

To run the tests in non-interactive mode, and discover all the tests, you can use the command:

```bash
python3 -m unittest discover tests
```

### Usage

* Start the console in interactive mode:

```bash
$ ./console.py
(hbnb)
```

* Use help to see the available commands:

```bash
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb)
```

* Quit the console:

```bash
(hbnb) quit
$
```

#### Commands

The commands are displayed in the following format: *Command / usage / example with output*

* Create

Creates a new instance of a given class. The class' ID is printed, and the instance is saved to the file file.json.

```bash
create <class>
```

```bash
(hbnb) create BaseModel
6cfb47c4-a434-4da7-ac03-2122624c3762
(hbnb)
```

* Show

```bash
show <class> <id>
```

```bash
(hbnb) show BaseModel 6cfb47c4-a434-4da7-ac03-212262
