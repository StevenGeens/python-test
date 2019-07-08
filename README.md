# Test project for Python
This is a test project to see how Python projects could be shared between multiple people

## Necessary Software
This focuses on Windows. (Mac is very similar and Linux people should use their package manager.)
1. [Git](https://git-scm.com/download/win) : Install with default options
2. [Python 3.7](https://www.python.org/downloads/windows/) (or higher) : Install with adding Python to the default PATH. 
3. [Pycharm Community edition](https://www.jetbrains.com/pycharm/download/#section=windows) : Make sure you select the community edition. Install with default options.

## Installation Instructions

1.  When starting for the first time Pycharm should have the following option. (It's also reachable from the File Menu.)
    **Checkout from version control**
2.  Select **Git** from the dropdown.
3.  Fill in `https://github.com/StevenGeens/python-test.git`
4.  Press the **Clone** button.
4.  Yes to open directory
5.  Open terminal (lower part of the screen)
6.  Type in: `pip install -U pipenv`
7.  Go to **File>Settings** (CTRL+ALT+S)
8.  Go to **Project: python-test> Project interpreter**
9.  Press the Gear Icon in the top right corner > **Add...**
10. Select **Pipenv** Environment.
    (All the settings should be automatically filled in.)
11. Click on **Ok**

This should result in the project automatically downloading all required packages.

You can now start main.py.


