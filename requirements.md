# Requirements and Setup

Instructions for setting up a scientific computing environment on your computer.
No experience with computer programing is required but you should be familiar
with your operating system and how to install software. Many of the examples
require the use of the command line so you should be to use the WIndows command
prompt, powershell or the bash terminal. The two primary tools for computing are
the command line terminal and a text editor.

In Windows to open the command prompt type the `Windows logo+R` to open the run
dialog. Type `cmd` or `powershell` and press enter. Press `Ctrl+Shift+Enter`
to run it with elevated privledges.

On a Mac click the Launchpad icon in the Dock, type Terminal in the search
field, then click Terminal.

On most Linux distributions the bash terminal can be opened with `Ctrl+Alt+T` or
search for Terminal in the application menu.

## Setup a Unix environment

Most of the software for this course is cross-platform and will run on any
uptodate operating system. You should use the one you ae most familiar with.
Most of the world's computers, from a ten dollar Raspberry Pi to a
million-dollar super computer, run on Linux so you should be at least a little
familliar with the Unix filesystem, bash terminal and system utilities,
especially the ones for accessing remote systems.

On Linux and Mac the default command line interpreter is bash, and most of the
core Unix utilities are installed by default so there's nothing to do.

On recent versions of Windows (Windows 10 or later) you can enable the Windows
Subsystem for Linux and install a Linux distro of your choice. The default is
Ubuntu and is a reasonable choice.

TODO: Instructions here.

## Get a GitHub account and install git

Git is a distributed version control system that lets you track changes and collaborate with other on projects. GitHub is a remote repository where you can host and share your projects. Microsoft owns it so...

Signup for GitHub: <https://github.com/signup>

### Install git

TODO: Instructions here.

Once you have git installed on your computer you can clone this repository.

- Click the green "Code" button and coppy the url. In a terminal run:  
   `git clone https://github.com/Westminster-Astronomical-Society/Python-for-astronomers.git`

- This is a work in progress and so there will be frequent changes. To get changes and updates, in the terminal cd into Python-for-astronomers and run:  
   `git pull`

## Install a text editor

The default text editor on most Unix systems is Vim. It is a lightwieght terminal based and is installed on almost all systems so if you need to edit a file on a remote system (eg. a Raspberry Pi) it is usually the easiest and fastest way to do it so it would be useful to know a little bit of Vim. It is a modal editor though so it takes some getting used to. If you type `vimtutor` in a bash terminal it will run you through a short tutorial on how to use it.

Most people however would prefer a modern text editor, Vim is a 1990s update to a 1970s program. One of the most poular is vscode from Microsoft. It has a lot of features that make it very convenient for programing Python.

- You can run it in a browser so there is nothing to install.

   <https://vscode.dev/>

- Or download and run the installer for your distribution.

   <https://code.visualstudio.com/download>

### vscode extensions

There are several extensions that will make Python programing in vscode a lot
easier. After vscode is started type `Ctrl+Shift+X` to open the extension
toolbar. In the search box type Python or Jupyter and install the **Python**,
**Pylance**, **Pylint** and **Jupyter**. It will also give you helpful
suggestions for extensions you might need, because that's what Microsoft does,
they give you helpfull sugestions. That can be disabled.
