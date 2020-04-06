---
layout: posts
title: "Absolute Python Tutorial for Beginners"
description: "Absolute Python Tutorial for Beginners"
image: /src/images/python.png
tags: [Python]
---

##### Contents:
   1. [Inroduction and setup](#introduction-and-setup)
   2. [Basic Concepts and Data Types](#basic-concepts-and-data-types)
<hr><br>

# Introduction and Setup
[<img src="/src/images/python_tut-1.png" class="img-fluid">](https://www.youtube.com/watch?v=rX5rNdQIhwg/)

Python is a high-level, interpreted, interactive and object-oriented scripting language. Python was designed to be 
highly readable which uses English keywords frequently where as other languages use punctuation and it has fewer 
syntactical constructons as other languages.

### History of Python:
Python was developed by Guido van Rossum in the late eighties and early nineties at the National Research Institute
for Mathematics and Computer Science in the Netherlands.

Python is derived from many other languages, including ABC, Modula-3, C, C++, Algol-68, SmallTalk, and UNIX shell
and other scripting languages.

Python is copyrighted. Like Perl, Python source code is now available under the GNU General Public License (GPL).

Python is now maintained by a core development team at the institute, although Guido van Rossum still holds a vital
role in directing its progress.

### Python Features:
   * Interpreted Language -> This means that it has processed at runtime by the interpreter and you do need to 
compile your program before executing it. This is simailar to PERL and PHP.

   * Interactive Mode -> Support for an interactive mode in which you can enter results from a terminal right to the
language, allowing interactive testingand debugging of snippets of code.

   * Object-Oriented Language -> Python supports functional and structured programmig methods as well as 
Object-Oriented style or technique of programming that encapsulates code within objects.

   * Easy-to-learn -> Python has relatively few keywords, simple structure and a clearly defined syntax. This makes 
Python a great language for the beginner programmers.

   * Easy-to-read -> Python code is much more clearly defined and short syntax.
 
   * Easy-to-manintain -> Python's success is that its source code is fairly easy-to-maintain.

   * A broad standard library -> One of Python's greatest strengths is the bulk of the library is very portable and
cross-platform compatible on Linux, Windows and MacOS.

   * Portable -> Python follows WORA neans Write-Once-Run-Anywhere that makes it available to wide variety of 
hardware platforms and has same interface to all platforms.

   * Extendable -> You can add low-level modules to the Python interpreter. These modules enable programmers to add
to or customize their tools to be more efficient.

   * Databases -> Python provides interfaces to all major commercial databases.

   * GUI Programming -> Python supports GUI applications that can be created and ported to many system calls, 
libraries and wide variety of hardware platforms.

   * Web Development -> With Python you can also develop fully functional website and web applications with help of 
different Python based frameworks like Django.

   * Scalable -> Python provides a better structure and support for large programs than shell scripting.

   * ...and more

## Python's Versions:
Python comes in two versions, namely, Python2.X and Python3.X. The major difference between two is that Python2.X
stores string in two objects, i.e., str and Unicode whereas Pyrhon3.X stores all string in Unicode. Also Python3.X
is more efficient and developers continously building libraries for it but Python2.X supports older libraries also.
The recommended verion to use is Python3.X. In the whole tutorial, we'll use Pyton3.X.

## Local Environment Setup:
Python is available on a wide variety of platforms including Linux and MacOS X.

### Getting Python:
The most up-to-date and current source code, binaries, etc. is available at the official website of Python.

[Python Official Website](https://www.python.org/)

### Install Python:
Python distribution is available to a wide variety of platforms. You need to downnload only the binary code 
applicable for your platform and install.

If the binary code for your platform is not available, you need a c compiler to comple the source code manually.
It offers more flexiblity in terms of choice of features that you require in your installation.

Here is a quick overview of installing Python on various platforms:

#### Linux and its Based Distros:
There are two methods of installing Python in Linux and its based distros:

##### Method 1:
   1. Open terminal or press Ctrl + Alt + T.

   2. #### Debian or Debian Based/Ubuntu:
      `sudo apt-get install python3`
      #### Arch or Arch based/Manjaro:
      `sudo pacman -S python3`
      #### Fedora:
      `sudo dnf install python3`
      #### OpenSUSE:
      `sudo yum install python3`

##### Method 2:
   1. Open a web browser and go to [Downlod Python](https://www.python.org/download/).

   2. Follow the link to download zipped source code available for UNIX/Linux.

   3. Download and extract.

   4. Editing the *Modules/Setup* file if you want to customize some options.

   5. **run** *./configure* script.

   6. make

   7. make install

This will install python in a standard location */usr/local/bin* and its libraries are installed in 
*/usr/local/lib/pythonXX* where XX is the version of Python that you are using.

In case, if python will not install in a standard location you can setup path in Linux:
   * Open a terminal or press **Ctrl + Alt + T**.

   * type `export PATH="$PATH:/usr/local/bin/python"` and press enter.

#### Windows Installation:
   1. Open a web browser and go to [Downlod Python](https://www.python.org/download/).

   2. Follow the link for the Windows installer *python-XYZ.msi* file where XYZ is the version.

   3. Run the downloaded file.

##### Setting PATH at Windows:
   * Open a command prompt.

   * type `path %path%;C:\Python` and press enter.

**Note:** C:\Python is the path of the Python directory.

#### MacOS Installation:
Recent Macs come with Python installed, but it may be several years out of date. See 
[Download Python for MacOS](https://www.python.org/download/mac/) for instructions on getting the current version 
along with extra tools to support development on Mac. For older MacOS's befor MacOS X 10.3 (released in 2003), 
MacPython is available.

## Runnig Python:
There are two ways to stat python:

### Interactive Interpreter:
You can enter **python**(if you installed Python2.X) or **python3**(if you installed Python3.X) and start coding
right away in the interactive interpreter by starting it from command line.

##### In Linux and MacOS:
`$ python`<br>
`Python 2.7.16 (default, Oct 10 2019, 22:02:15)`<br> 
`[GCC 8.3.0] on linux2`<br>
`Type "help", "copyright", "credits" or "license" for more information.`<br>
`>>>` 

          OR

`$ python3`<br>
`$Python 3.7.3 (default, Dec 20 2019, 18:57:59)`<br> 
`[GCC 8.3.0] on linux`<br>
`Type "help", "copyright", "credits" or "license" for more information.`<br>
`>>>` 

##### In Windows:
`C:>python` # Wndows/DOS

### Integrated Development Environment:
You can run Python from a GUI environment as well. All you need is a GUI application on your system that supports 
Python.

There are many IDE available like [VS Code](https://code.visualstudio.com/), Atom, Sublime, PyCharm, etc.

In whole tutorial, we'll be using [VS Code](https://code.visualstudio.com/).



# Basic Concepts and Data Types
[<img src="/src/images/python_tut_2.png" class="img-fluid">](https://www.youtube.com/watch?v=NlAtwCILAoQ/)
The Python language has many similarities to Perl, C/C++ and Java. However, there are some definite differences
between the languages. Here is a quick overview:

Before going to proceed, you must know there are two ways to represent numbers:
   * Integer -> The number which doesn't contain decimal points. e.g. 2, 100, -7, etc.
  
   * Floats -> The number which contains decimal point. e.g. 2.007, 1.4, -78.0, etc.

### Simple Operations:

There are simple numerical operations that are used in Python:

`>>> 5 + 2   #Addition` <br>
`7` <br>
`>>> 5 - 2   #Subtraction` <br>
`3` <br>
`>>> 5 * 2   #Multiplication` <br>
`10` <br>
`>>> 5 ** 2  #Exponentation` <br>
`25` <br>
`>>> 9 ** (1/2)` <br>
`3.0` <br>
`>>> 5 / 2   #Division Gives Float Value` <br>
`2.5` <br>
`>>> 5 // 2  #Quotient` <br>
`2` <br>
`>>> 5 % 2   #Remainder` <br>
`1`

### Strings:
If you want to use text in Python, you have to use a **string**.

A **string** is created by entering text between **two single or double quotation marks**.

When the Python console displays a string, it generally uses single quotes. The delimiter used for a string doesn't
affect how it behaves in any way.

`>>> "Hello World!"` <br>
`'Hello World!'` <br>
`>>> 'Python is fun!'` <br>
`'Python is fun!'` 


Some characters can't be directly included in a string. For instance, double quotes can't be directly included in a
dounle quote string; this would cause it to end prematurely.

Characters like these must be escaped by placing a **backslash (\)** before them. Other common characters that must 
be escaped are *newlines* and *backslashes*. 
Dounle quotes only need to be escaped in double quote strings, and the same is true for single quote string.

`>>> "I\m Programmer!"` <br>
`>>> 'I'm Programmer!'`

### Simple Input and Output:
##### Output:
Usually, programs take **input** and process it to produce **output**.
In Python, you can use the **print** function to produce output. This displays a textual representation of something
to the screen.

`>>> print(5 * 2.5)` <br>
`12.5` <br>
`>>> print("Hello\nWorld!")` <br>
`Hello` <br>
`World!`

**Note:** When a string is printed, the quotes aroud it are not displayed.

##### Input:
To get input from the user in Python, you can use **input** function.
The function prompts the user for input, and returns what they enter as a string (with the contents automatically 
escaped).

`>>> input("Enter something: ")` <br>
`Enter something: Hi` <br>
`'Hi'`

### Lines and Indentation:
One of the first cavets programmers encounter when learning Python is the fact that there are no braces to indicate
blocks of code for class and function defination or flow control. Blocks of code are denoted by line indentation, 
which is rigidly enforced.

The number of spaces in the indentation is variable, but all statements within the block must be indented the same 
amount. Both blocks in this example are fine:
```python
if True:
    print("Answer")
    print("True")
else:
 print("Answer")
 print("False")
```
However, the second block in this example will generate an error:
```python
if True:
    print("Answer")
    print("True")
else:
 print("Answer")
    print("False")
```
**Note:** Don't try to understand logic. Just make sure you understood how line indentation is used.

### Comments in Python:
A hash sign (#) that is not inside a string literal begins a comment. All characters after the # and up to the 
physical line end are part of the comment and the Python interpreter ignores them.
This is useful when you want to make note in Python script.
```python
#!/usr/bin/python3

# First Comment
print("Hello World!") # Second Comment
```
This will produce the following result:

`Hello World!`

### Variables:
**Variables** plays a very important role in most programming languages, and Pyhon is no exception. A variable allows
you to store a value by assigning it to a name, which can be used to refer to the value later in the program.

To assign a variable, use **one equal sign**. Unlike, most lines of code we've looked at so far, it doesn't produce
any output.

<img src="/src/images/mem_loc_1.jpg" class="img-fluid" height="500px" width="500px">

`>>> x = 7` <br>
`>>> print(x + 6)` <br>
`13` <br>
`>>> print(x)` <br>
`7`

Variables can be reassigned as many times as you want, in order to change value. In Python, variables don't have 
specific types, so you can assign a string to variable, and later assign an integer to the same variable.

`>>> x = 4.76` <br>
`>>> print(x)` <br>
`4.76` <br>
`>>> x = "Hello World!"` <br>
`>>> print(x)` <br>
`Hello World!`

Certain restrictions apply in regard to the characters that may be used in Python variable names known as 
**Identifier**. The only characters that are allowed are letters, numbers and underscores, Also, they aren't start 
with numbers.
Not following these rules results in errors.

`>>> variable_example = 2` <br>
`>>> 12r = 4.4` <br>
  `File "<stdin>", line 1` <br>
    `12r = 4.4` <br>
      `^` <br>
`SyntaxError: invalid syntax` <br>
`>>> spaces are not allowed` <br>
  `File "<stdin>", line 1` <br>
    `spaces are not allowed` <br>
             `^` <br>
`SyntaxError: invalid syntax` 

**Note:** Python is a case sensitive programming language. Thus, *Name* and *name* are two different variables.

##### Reserved Words:
The following list shows the reserved words in Python. These reserved words may not be used as constants or variable
or any other identifier names. All he Python keywords contain lowercase letters only.

<table class="table-responsive table table-striped table-bordered table-hover" border="1" cellpadding="10" cellspacing="10">
    <tr>
        <td>and</td>
        <td>assert</td>
        <td>break</td>
        <td>class</td>
        <td>continue</td>
        <td>def</td>
    </tr>
    <tr>
        <td>del</td>
        <td>elif</td>
        <td>else</td>
        <td>expect</td>
        <td>exec</td>
        <td>finally</td>
    </tr>
    <tr>
        <td>for</td>
        <td>from</td>
        <td>global</td>
        <td>if</td>
        <td>import</td>
        <td>in</td>
    </tr>
    <tr>
        <td>is</td>
        <td>lambda</td>
        <td>not</td>
        <td>or</td>
        <td>pass</td>
        <td>print</td>
    </tr>
    <tr>
        <td>raise</td>
        <td>return</td>
        <td>try</td>
        <td>while</td>
        <td>with</td>
        <td>yield</td>
    </tr>
</table>


Trying to reference a variable you haven't assigned to causes an **error**.
To delete a variable, you can use **del** keyord. Deleted variables can be reassigned to later as normal.

`>>> foo = input("Enter no.: ")` <br>
`Enter no.: 3` <br>
`>>> print(bar)` <br>
`Traceback (most recent call last):` <br>
  `File "<stdin>", line 1, in <module>` <br>
`NameError: name 'bar' is not defined` <br>
`>>> print(foo)` <br>
`3` <br>
`>>> del foo` <br>
`>>> print(foo)` <br>
`Traceback (most recent call last):` <br>
  `File "<stdin>", line 1, in <module>` <br>
`NameError: name 'foo' is not defined` 

##### Multiple Assignment:
Python allows you to assign a single value to several variables simultaneously. For example:

`>>> a = b = c = 1` <br>
`>>> print(a, b, c)` <br>
`1 1 1`

Here, an integer object is created with the value of 1, and all three variables are assigned to the same memory 
location. You can also assign multiple objects to multiple variables. For example:

`>>> a, b, c = 1, 2, "Max"` <br>
`>>> print(a, b, c)` <br>
`1 2 Max`

Here, two integer objects with values 1 and 2 are assigned to variables a and b, and one string object with the 
value "Max" is assigned to the variable c.

### Standard Data Types:
The data stored in menory can be of many types. For example, a person's age is stored as numeric value and his or 
her address is stored as alphanumeric characters. Python has various standard data types that are used to define the
operations possible on them and the storage method for them.

Python has five standard data types:

   * Numbers
   
   * String

   * List

   * Tuple

   * Dictionary


