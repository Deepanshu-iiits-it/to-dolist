# to-dolist
A Command-line to-do list application built using the 'Argparse' library of Python that allows users to keep a record of to-do and done tasks and run commands using the terminal.

This project is a command-line todo list application that allows users to add new todos, delete todos, mark them as done, see a report of existing todos and done tasks, etc. This project is a command-line project that allows users to run commands in the terminal for different operations like adding, deleting, and viewing todos and done tasks.

Two Python libraries are used in this project: 'Argparse' and 'Datetime'. 'Argparse' library is used to make it a command-line application to perform tasks using command-line instructions. Usage of the application is:

To add a new todo, run
```python todo.py add "todo item"```
 
To show remaining todos, run
```python todo.py ls ```
 
To delete a todo, run
```python todo.py del NUMBER```
 
To complete a todo, run
```python todo.py done NUMBER```
 
To show usage, run
```python todo.py help``` or ```python todo.py```
 
To see Statistics, run
```python todo.py report```
 
'Datetime' library is used to maintain the record of time on which a todo is marked as done and how many todo tasks are there at any time.
This project requires two text files: 'todo.txt' and 'done.txt', to maintain the todos and done tasks.
