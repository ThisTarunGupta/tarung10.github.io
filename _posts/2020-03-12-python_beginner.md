---
layout: posts
title: "Absolute Python Tutorial for Beginners"
description: "Absolute Python Tutorial for Beginners: Introduction and Setup... History... Features... Installation... Runnung..."
image: /src/images/python.png
tags: [python]
---

##### Contents:
   1. [Inroduction and setup](#introduction-and-setup)

<hr><br>

# Introduction and Setup:
[<img src="/src/images/python_tut-1.png" class="img-fluid">](https://youtu.be/rX5rNdQIhwg)
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

There are many IDE available like [VS Code](https://code.download.org/), Atom, Sublime, PyCharm, etc.

In whole tutorial, we'll be using [VS Code](https://code.download.org/).
