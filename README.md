# Pandas Cookbook
This is the code repository for [Pandas Cookbook](https://www.packtpub.com/big-data-and-business-intelligence/pandas-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781784393878), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will provide you with unique, idiomatic, and fun recipes for both fundamental and advanced data manipulation tasks with pandas. Some recipes focus on achieving a deeper understanding of basic principles, or comparing and contrasting two similar operations. Other recipes will dive deep into a particular dataset, uncovering new and unexpected insights along the way. 

The pandas library is massive, and it’s common for frequent users to be unaware of many of its more impressive features. The official pandas documentation, while thorough, does not contain many useful examples of how to piece together multiple commands like one would do during an actual analysis. This book guides you, as if you were looking over the shoulder of an expert, through practical situations that you are highly likely to encounter.


## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
>>> employee = pd.read_csv('data/employee')
>>> max_dept_salary = employee.groupby('DEPARTMENT')['BASE_SALARY'].max()
```

Pandas is a third-party package for the Python programming language and, as of the printing of this book, is on version 0.20. Currently, Python has two major supported releases, versions 2.7 and 3.6. Python 3 is the future, and it is now highly recommended that all scientific computing users of Python use it, as Python 2 will no longer be supported in 2020. All examples in this book have been run and tested with pandas 0.20 on Python 3.6.



In addition to pandas, you will need to have the matplotlib version 2.0 and seaborn version 0.8 visualization libraries installed. A major dependence for pandas is the NumPy library, which forms the basis of most of the popular Python scientific computing libraries.

There are a wide variety of ways in which you can install pandas and the rest of the libraries mentioned on your computer, but by far the simplest method is to install the Anaconda distribution. Created by Continuum Analytics, it packages together all the popular libraries for scientific computing in a single downloadable file available on Windows, Mac OSX, and Linux. Visit the download page to get the Anaconda distribution (https://www.anaconda.com/download).

In addition to all the scientific computing libraries, the Anaconda distribution comes with Jupyter Notebook, which is a browser-based program for developing in Python, among many other languages. All of the recipes for this book were developed inside of a Jupyter Notebook and all of the individual notebooks for each chapter will be available for you to use.

It is possible to install all the necessary libraries for this book without the use of the Anaconda distribution. For those that are interested, visit the pandas Installation page (http://pandas.pydata.org/pandas-docs/stable/install.html).

## Related Products
* [Robot Operating System Cookbook](https://www.packtpub.com/hardware-and-creative/robot-operating-system-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781783987443)

* [PostGIS Cookbook - Second Edition](https://www.packtpub.com/application-development/postgis-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788299329)

* [Windows Presentation Foundation Cookbook](https://www.packtpub.com/application-development/windows-presentation-foundation-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781788399807)


