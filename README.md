# Prerequisites

## Hardware
(1 minute to open your laptop and login to github)

This tutorial assumes you're using a Mac computer (laptop or desktop)

## Book
(1 minute to open the book)

We'll be following the book "Python Programming for the Absolute Beginner, 3rd Edition"

[Electronic copy: https://github.com/CWade3051/Py/...]( https://github.com/CWade3051/Py/blob/master/Absolute%20Book/Python%20Programming%20for%20the%20Absolute%20Beginner%2C%203rd%20Edition/Python%20Programming%20for%20the%20Absolute%20Beginner%2C%203rd%20Edition.pdf)


## Skills

### Running shell commands
(3 minutes to learn how to use the Terminal app)

You need to know how to run shell commands:
1. In manuals and online sometimes you'll see Shell commands that you want to run for actions, such as installing a new version of python. Let take a toy example of a Shell command. It looks like this: `echo Hello World`
1. Copy the command from the manual. Use copy-and-paste (not typing) for accuracy.
2. Open the Terminal (fastest way to find the Terminal on Mac is to type "ter" in the Spotlight Search - which is the magnifying glass in the top right)
3. Paste the command and hit Enter
4. Once Terminal is open, right-click on its icon in your Mac's Dock and select Options -> Keep in Dock (that way you don't have to look for the Terminal every time you need it)


## Software Tools
(20 minutes to install Atom, Xcode, Brew, and Python 3)

Install the text editor:
1. Got to https://atom.io/
2. Click Download for Mac
3. Go through the installation
4. Once Atom is open, right-click on its icon in your Mac's Dock and select Options -> Keep in Dock (that way you don't have to look for the Text Editor every time you need it)

While text editor installs, install Python 3 (also Xcode and Brew)
https://www.google.com/search?q=install+python+3+mac
(follow the "Doing it Right" section of the webpage "Installing Python 3 on Mac OS X: The Hitchhiker's Guide to Python")
The page will show you how to install Apple Xcode which is a perquisite for installing Python 3 via the Brew package manager.

Make the command "python" always open "python3.5" (the default on Mac is python2.6)
Open Terminal and run:
```
echo -e '\nalias python="/opt/homebrew/bin/python3.5"' >> ~/.bash_profile
```

## Editor Setup
(10 minutes to get familiar and Setup)

Install Atom's "script-runner" package so we can run Python directly from the text editor

1. Follow [this video tutorial](https://www.youtube.com/watch?v=QyVnWjZzGVY
), yet instead of [**script** by rgbkrk](https://atom.io/packages/script) look for [**script-runner** by ioquatix](https://atom.io/packages/script-runner)
2. In the same way as above, install [MagicPython by MagicStack](https://atom.io/packages/MagicPython) - it's a programing language syntax highlighter - uses color to show various parts of the code


# Chapter 1

(30 minutes)

Skip the "Setting Up Python" sections. They are already covered in Prerequisites.

When you get to the "Introducing IDLE" section,

1. Under "Writing your first program" just open your Mac Terminal, type "python" and hit Enter.
2. Under "Writing your first program (again)"
    1. Open Atom 
    2. The screenshot in the Book is not relevant because we're using Atom - in Atom there will be no "Run" button. Instead will use a keyboard shortcut Ctrl-x  
    3. Write the program
    4. At the very top of the program add this line (copy-and-paste): `#!/opt/homebrew/bin/python3.5`
    5. Press Ctrl-x to run the program [instead of the "Run" button as described in the book] 


# Chapter 2

(2+ hours)

When you need to "Save" the `.py` files (your program), just save it to your Desktop for now. In later chapters you will learn how to save code to github.

1. When you get to typing the ASCII art "GAME OVER" on page 17, you'd probably want to look ahead and read about ASCII art on page 21. When typing up the code, you can give it more zest by doing a copy-and-paste of the ASCII art from http://patorjk.com/software/taag/#p=display&f=Star%20Wars&t=Game%20AOver yet I encourage you to to "draw" some of your own ASCII art. This helps develop comfort with editing raw text (which is what programming is) and muscle memory to better handle the text editor.
2. When you get to "Sounding the System Bell" section, open your Terminal and type "python" instead of using Atom to run the code. Make sure the sound is "On" on your Mac.
