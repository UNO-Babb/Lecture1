# Lecture 1
## Overview of the course
  - [Syllabus](CYBR%202980%20Syllabus%20-%20Python%20Programming.docx)

### Computer Hardware
![Von Neumann Architecture](https://upload.wikimedia.org/wikipedia/commons/e/e5/Von_Neumann_Architecture.svg)

### Data representation
  - Binary Numbers
  - [Flippy-Do](https://drive.google.com/file/d/0B6iNirqJ5EuVVTlla0RpR2RIa2s/view?usp=sharing)
  - [Binary Game](https://studio.code.org/projects/applab/iukLbcDnzqgoxuu810unLw)

### Scripting vs. Compiled Languages
#### Compiled Languages
- Written with strict syntax in high-level language
- Converted to machine code by the compiler
  - All lines are evaluated
  - Syntax errors are flagged by compiler
- Compiled program is what actually runs
- Used for major applications
- Source code is not needed for execution

#### Scripting Languages
- Written with strict syntax in high-level language
- Each line is converted to machine code as it runs
  - Syntax errors are not flagged until the individual line is executed
  - Conversion as you go is slower than converting ahead of time
- Easier to begin a program
- Used for automation and simple tasks
- Source code is needed to run

### Command Line Python
We will use a IDE (Integrated Development Environment) in this class. However, with python, you can type commands directly into a command line and they will execute. This is useful if you have a small script that you want to run or a bit of code you want to test outside of a larger program.

Launch the command line on your computer. Hit the Windows key then type CMD and launch Command Prompt from the Start menu.

To start, type python in the command prompt.

```
>>> print("Hello Python")

>>> print(2 + 3)

>>> print("Hello" + "world")

>>> print("Hello" + 5)
```
### Running Python from a file
Create a file using any text editor. Notepad or Notepad++ are installed on your computer and will work fine. Here is an example file.
[Hello.py](Hello.py)

After creating the file, save it on your desktop. In your command line, change directory to the desktop by typing the following commands.

```
cd desktop
python Hello.py
```

### Debugging Python
Type the following commands into a Python command session. Debug the errors to see how Python responds if it cannot run a command as typed.

```
>>> Print("Hello world")

>>> print "Hello world"

>>> print("Hello world)

>>> print("Hello world"

>>> print(Hello world)
```

### Getting Help
There are many internet resources, your peers, texts, and your instructor you can get help from in this class. Python also has built-in help documentation if you need it.

In a Python command session, type the following.

```
>>> help()

help> print

help> quit
```
### Quiz
1. Convert the following decimal number to binary
	- 22

1. Convert the following binary to decimal
  - 00011011

1. Which of the following would be considered an "input device" (Select all that apply)
	+ Keyboard
	- Printer
	+ Microphone
	- Speaker
	- Projector
	+ Bluetooth Antenna
	+ Touchscreen

1. Which of the following would be considered an "output device" (Select all that apply)
	- Keyboard
	+ Printer
	- Microphone
	+ Speaker
	+ Projector
	+ Bluetooth Antenna
	+ Touchscreen

1. Using command line help, what does ord do in python
	+ Return the Unicode point for a one-character string
	- Give you the shortest route to the Airport
	- Calculate the value of an algebraic function
	- Return the letter given a numeric value

1. Identify the bug in the following line of code?
```
	print("Hello world')
```
  - Print should be capitalized
  - Parenthesis are not needed
  - Single-quotes may not be used in print statements
  + Single-quotes and double-quotes cannot be paired

1. At the command prompt, I typed the following command:
```
  C:\Users\UNOStudent> python test.py
```
  I get the following error:
```
  python: can't open file 'test.py': [Errno 2] No such file or directory
```
  What might be the problem (select all that apply):  
	- Python may not be installed on this computer
	+ test.py may not exist in this directory... change directories using CD command
	+ test.py may exist but may be capitalized ie TEST.py
	- test.py is run but has a bug in the code

### For next class
- Sign up for a [GitHub](https://github.com) account
- Sign up for a [Repl.it](https://repl.it/) account
---
### Resources
Kapooht [CC BY-SA (https://creativecommons.org/licenses/by-sa/3.0)]  
Code.org (https://curriculum.code.org/csp-19/unit1/5/)  
