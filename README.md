# What is modules?
A module is a file or collection of code that can be reused in other programs. It usually contains functions, classes or variables.
**Example: **

Import math
                                                    print(math.sqrt (25))

## 1.Importing Modules
To reuse existing classes, functions or variables from other files or libraries.
Here are some common ways:
					Import math
				         print(math.sqrt(16))

These are the common ways to import the module.

    1.     from math import sqrt
print(sqrt(16))
      2.      Import math as m
                                                                         print(m.sqrt(25))
## 2. Built in modules
Built in modules are modules that come pre –installed with python –you don’t need to install them manually. You can just import them and start using their features right way.
Some built in modules
-	Math operations
-	Random number generation
-	Date / Time handling
-	File System access
-	System info
## 3.Creating Modules
Creating Modules is very simple –you just write python code in a separate file and import it into other files.
## 4.Using as keyword
The as keyword is used to give a module, function, or object a custom name when importing.
**Syntax**
				Import math as m

## 5.dir() function
The dir() function is a built in python function used to list all the names (variables, functions, classes etc.) defined in a module, object, or the current scope.
## 6. Packages
A package is a way to organize related python modules into a directory structure. It helps you  group similar functionality together, making your code modular, reusable, and easier to maintain.
## 7.Installing packages
Pip is the python package installer
It downloads and installs packages from the python package index (PyPI) –the official repository of python packages.
**Syntax**
			Pip install package_name
## 8.Virtual Environment
A virtual Environment is an isolated workspace where you can install python packages without affecting your system –wide python installation or other projects.





