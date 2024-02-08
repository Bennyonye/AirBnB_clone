# AirBnB Clone Project - The Console

![AirBnB Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Airbnb_Logo_B%C3%A9lo.svg/1280px-Airbnb_Logo_B%C3%A9lo.svg.png)

## Project Description

The AirBnB Clone project is an endeavor to replicate the core functionalities of the renowned platform Airbnb. In this initial phase, the focus is on developing a command-line interpreter (CLI) to handle AirBnB objects. This CLI lays the groundwork for subsequent tasks such as HTML/CSS templating, database storage, API integration, and front-end development.

## Command Interpreter Overview

The command interpreter, implemented in `console.py`, acts as a tool for interacting with and managing AirBnB objects. It enables users to perform operations like creating, retrieving, updating, and deleting objects. Modeled after a Shell-like interface, the interpreter provides commands for manipulating AirBnB objects.

## Getting Started

To launch the AirBnB Clone command interpreter, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/AirBnB_clone.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AirBnB_clone
   ```

3. Run the command interpreter:

   ```bash
   ./console.py
   ```

## Usage Guide

Once the command interpreter is running, you can utilize the following commands to manage AirBnB objects:

- `create`: Create a new AirBnB object (e.g., User, State, City, Place).
  Example:
  ```bash
  (hbnb) create User
  ```

- `show`: Retrieve information about a specific object by specifying its class name and ID.
  Example:
  ```bash
  (hbnb) show User 1234-5678-9012
  ```

- `all`: List all objects of a given class or list all objects if no class is specified.
  Example:
  ```bash
  (hbnb) all
  (hbnb) all State
  ```

- `update`: Update attributes of an object by specifying its class name, ID, attribute name, and attribute value.
  Example:
  ```bash
  (hbnb) update User 1234-5678-9012 first_name "John"
  ```

- `destroy`: Delete an object by specifying its class name and ID.
  Example:
  ```bash
  (hbnb) destroy Place 9876-5432-1098
  ```

- `quit` or `EOF`: Exit the command interpreter.
  Example:
  ```bash
  (hbnb) quit
  ```

- `help`: Display a list of available commands or get help for a specific command.
  Example:
  ```bash
  (hbnb) help
  (hbnb) help show
  ```

## Examples

Here are some examples illustrating the usage of the AirBnB Clone command interpreter:

1. Creating a new User object:
   ```bash
   (hbnb) create User
   ```

2. Listing all City objects:
   ```bash
   (hbnb) all City
   ```

3. Updating the name attribute of a Place object:
   ```bash
   (hbnb) update Place 1234-5678-9012 name "Cozy Cabin"
   ```

4. Deleting a State object:
   ```bash
   (hbnb) destroy State 9876-5432-1098
   ```

5. Exiting the command interpreter:
   ```bash
   (hbnb) quit
   ```

The AirBnB Clone command interpreter offers a convenient means to manage and manipulate AirBnB objects, serving as an indispensable tool for the development of the full-fledged AirBnB clone web application.

## Authors
   + Benedict Igbukolu
