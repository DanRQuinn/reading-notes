# The Coders Computer

## Choosing a Text editor

When choosing a text editor it is important to think about personal preferance. Many editors are capable of coding but picking one that works for you is important.

Color coding and interface and even the theme can make it easier to navigate or easier on the eyes.

The only way to find out is to get your hands dirty, experimentation with various text editors will help you find your favorite, even if they all do about the same thing.

Main features: 

"1.) code completion; 2.) syntax
highlighting; 3.) a nice variety of themes (to reduce eye strain and
fatigue); and 4.) the ability to choose from a healthy selection of
extensions available when you need them"

Quote from [Choosing A Text Editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

Text Edit doesnt have all the features that many third party text editors have.

Notepad++, Text Wrangler, BB Edit, Visual Studio Code, Atom,
Brackets, and Sublime Text are all good options.

## The Command Line

"A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text."

Quote from: [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

You type in a command or promt and then the next lines will be output before giving another command prompt

To open in MAC use command space and type "term" then enter

The shell determines how your terminal reacts and behaves after running commands.

There are many shortcuts that can make your life easier you just have to look them up.

## Basic Navigation

From: [Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)

Root directory breaks down into sub directories

Use tab too complete paths this will save time

cd = home directory or change directories

PWD = Current location

ls = list directories in current directory

~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).

.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

## More about files

From: [more about files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

Everything is a file

files are case sensitive

spaces are bad and break up command lines use 'quotes' to fix this is you use tab completion this will also ignore the spaces in the file name.

ls -a Documents the a shows hidden files

 A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:

file.exe - an executable file, or program.

file.txt - a plain text file.

file.png, file.gif, file.jpg - an image.

## Questions and answers

1. What are four important features to look for in a text editor?

2. What do the following commands do?

-1. pwd = Current directory

-2.ls = list directories

-3. cd = change directory

-4. mkdir = make new folder

-5. touch = create file

3. Can you explain what is happening in the following scenario if these commands and arguments are entered into the command line? (Arguments are extra instructions given to a command.)

-1. cd projects = go to projects directory

-2. mkdir new-project = make folder called new-project

-3. touch new-project/newfile.md = make file called new-project/newfile.md

-4. cd .. = go back 1 directory

-5. ls projects/new-project = list files in new-projects folder inside projects folder
