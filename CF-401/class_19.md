# Automation

## Questions

- How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?

Regular expressions in Python can be used to search for specific patterns in strings using the re module. It provides functions like search() and match() to find patterns within a string, and the sub() function to substitute or manipulate strings based on patterns. By compiling a pattern with re.compile(), you can reuse it efficiently across multiple searches.

- What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?

The shutil module in Python serves the purpose of file and directory management. It offers a higher-level interface for tasks such as copying, moving, renaming, and deleting files and directories. For example, you can use shutil.copy() to duplicate a file or shutil.move() to relocate it. This module simplifies common file operations and provides an abstraction layer over the lower-level os module.

- Compare and contrast the os and shutil modules. When would you choose to use one over the other?

os is a low-level module that provides access to the operating system. It provides functions for tasks such as creating and deleting files and directories, changing the current directory, and getting the file system path. shutil is a high-level module that provides a simplified interface for file and directory operations. It provides functions for tasks such as copying, moving, and deleting files and directories. You would use os when you need to have fine-grained control over the operating system. For example, if you need to create a directory with specific permissions, you would use the os.mkdir() function. You would use shutil when you want to perform a common file or directory operation in a simple way. For example, if you want to copy a file to another location, you would use the shutil.copy() function.

