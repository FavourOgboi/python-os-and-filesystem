# Working with Files in Python

This repository contains a Jupyter notebook file that covers the basics of working with files in Python using the built-in `os` and `shutil` modules. It also covers other related topics such as file paths, directory navigation and file metadata.

## Topics Covered
- Introduction to the `os` module
- Navigating the file system with `os.path`
- Reading and writing files with `open()`
- Copying, moving, and deleting files with `shutil`
- File metadata using `os.stat()`
- Creating and removing directories with `os.mkdir()` and `os.rmdir()`

## Getting Started
To use the notebooks in this repository, you will need to have a working installation of Python and Jupyter Notebook. You can download the latest version of Python from the official website (https://www.python.org/) and install Jupyter Notebook by running `pip install jupyter`.

Once you have the necessary software installed, you can clone or download this repository to your local machine. Then, open a terminal or command prompt and navigate to the directory where you downloaded the repository. Run the command `jupyter notebook` to launch the Jupyter Notebook application.

In the Jupyter Notebook interface, navigate to the Working with Files in Python repository and open the notebook files to begin working through the tutorials.

## Examples
Here's an example of how you can use the `os` module to navigate the file system:
```python
import os

# Print the current working directory
print(os.getcwd())

# Change the current working directory
os.chdir('/path/to/directory')

# Print the current working directory again
print(os.getcwd())
