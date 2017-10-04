# Prerequisites

## Prerequisites: Hardware
(1 minute open your laptop and login to github)

This tutorial assumes your using a Mac computer (laptop or desktop)

Open your browser and go to https://github.com/alevchuk/programming-lessions


## Prerequisites: Book
(1 minute to open the book)

We'll be following the book "Python Programming for the Absolute Beginner, 3rd Edition"

Electronic copy https://github.com/CWade3051/Py/blob/master/Absolute%20Book/Python%20Programming%20for%20the%20Absolute%20Beginner%2C%203rd%20Edition/Python%20Programming%20for%20the%20Absolute%20Beginner%2C%203rd%20Edition.pdf


## Prerequisites: Skills
(3 minutes to lear how to use the Terminal app)

You need to know how to run shell commands:
1. Copy the command from the manual. Use copy-and-paste (not typing) for accuracy.
2. Open the Terminal (fastest way to find the Terminal on Mac is to type "ter" in the Spotlight Search - which is the magnifying glass in the top right)
3. Paste the command and hit Enter
4. Once Terminal is open, right-click on it's icon in your Mac's Dock and select Options -> Keep in Doc (that way you don't have to look for the Terminal every time you need it)


## Prerequisites: Software Tools
(20 minutes to install Atom, Xcode, Brew, and Python 3)

Install the text editor:
1. Got to https://atom.io/
2. Click Download for Mac
3. Go through the installation
4. Once Atom is open, right-click on it's icon in your Mac's Dock and select Options -> Keep in Doc (that way you don't have to look for the Text Editor every time you need it)

While text editor installs, install Python 3 (also Xcode and Brew)
https://www.google.com/search?q=install+python+3+mac
(follow the "Doing it Right" section of the webpage "Installing Python 3 on Mac OS X: The Hitchhiker's Guide to Python")
The page will show you how to install Apple Xcode which is a perquisite for installing Python 3 via the Brew package manager.

Make the command "python" always open "python3.5" (the default on Mac is ptyhon2.6)
Open Terminal and run:
  echo -e '\nalias python="/opt/homebrew/bin/python3.5"' >> ~/.bash_profile


## Prerequisites: Editor Setup
(10 minutes to get familiar and Setup)

Install Atom's "Script" package so we can run Python directly from the text editor

Follow this video tutorial
https://www.youtube.com/watch?v=QyVnWjZzGVY

In the same way as above, install "MagicPython" (a syntax highlighter by MagicStack)
