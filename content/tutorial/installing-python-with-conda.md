+++
title = "Installing Python using Conda"
date = "2018-01-31"
author = "Matt Murbach"
authorLink = "http://mattmurbach.com"
tags = ["python"]
banner = "img/tutorials/python-conda.png"
categories = ["Python"]
+++

This page is the first post in a series of introductory python tutorials: \\
1. Installing Python using Conda - *this tutorial*\\
2. [Getting started with Jupyter]({{< ref "tutorial/getting-started-with-jupyter.md" >}})\\
3. [Using Python packages]({{< ref "tutorial/using-python-packages.md" >}})\\
4. [Working with data]({{< ref "tutorial/working-with-data.md" >}})\\
5. [Making figures in Python]({{< ref "tutorial/making-figures-with-python.md" >}})
<!--more-->
<hr>

To begin using Python, we first need to install it. For these tutorials, we will be using Python 3.7, although any Python 3 should work.

If you do not already have Python 3 installed on your computer (or even if you do, but don't yet use conda), we recommend installing miniconda (which includes the conda package manager and Python).
Installation instructions for your OS can be found at [https://conda.io/miniconda.html](https://conda.io/miniconda.html).

<div class="alert alert-primary">*Note:* Windows users, if you want to be able to use the conda command in the command prompt or Git BASH, make sure to that the "Add Conda to my PATH environment variable" box is checked during installation.</div>

After you have installed conda, you can run the following commands in your Terminal/command prompt/Git BASH to update and test your installation:

1. Update conda’s listing of packages for your system: `conda update conda`
2. Test your installation: `conda list`
    - For a successful installation, a list of installed packages appears.
3. Test that Python 3 is your default Python: `python -V`
    - You should see something like `Python 3.7.x :: Anaconda, Inc.`

You can interact with Python at this point, by simply typing `python`.

Try executing the following statements in this interactive environment:
```shell
>>> a = 5
>>> print(a) <br>
5
>>> myName = 'Mark'
>>> print('Hi, my name is {}!'.format(myName))
Hi, my name is Mark!
```

To exit out of this interactive Python session, type `exit()`.

If you've made it this far, congratulations!
You now have Python 3 and Conda installed on your computer and you're ready to move on to [Part 2. Getting Started with Jupyter]({{< ref "tutorial/getting-started-with-jupyter.md" >}}).
