+++
title = "Installing Git and a Shell"
date = "2018-01-22"
author = "Matt Murbach"
authorLink = "http://mattmurbach.com"
tags = ["git"]
banner = "img/tutorials/git-logo.png"
categories = ["Version control", "git"]
+++

### git and github
git is a system used for version control and collaboration.

**You should have a github account and ensure that
git is installed on your computer.**

### Bash shell and git software version control
The bash shell provides a programming environment that
is often used to manipulate files, install programs, and
basic data analysis.
The git version control system (along with the github website)
are widely used for sharing codes and collaborative development
of software.
Bash and git are part of Linux and Mac OSX.
Windows users should install gitbash. (See https://git-scm.com/download/win.)
Look here for more
details on the use of an editor with Windows for git.

Mac OSX note: Some folks reported an error with git:
```
xcode-select: note: no developer tools were found at '/Applications/Xcode.app', requesting install. Choose an option in the dialog to download the command line developer tools.
```
To fix this, do the following:

- Start a new Terminal
- Run the following command: xcode-select --install
- Click Install
- Click Agree to agree to the terms

For more information see this link

Windows user note:

Windows users should install the Software Carpentry recommended software:

Please follow these instructions on YouTube: https://www.youtube.com/watch?v=339AEqk9c-8.
Make sure you install gitbash and the text editor (SWCarpentryInstaller).
Links to the installers for Windows:

- GitBASH: https://git-for-windows.github.io
- Software Carpentry Installer: https://github.com/swcarpentry/windows-installer/releases/

### Text editor
Folks will select a text editor of their choice, such as
Notebook (Windows), vim (all platforms), and sublime (all platforms).
A text editor is different from word processing programs,
like MS Word, in that text editors often recognize
program syntax and do no formatting.

If you don't already have a favorite text editor, we recommend installing either atom or Sublime, which are both available for all platforms.

### Conda and Python
Conda is a system for installing and otherwise managing Python and other
software packages. The installation of Python and Conda are covered in a [separate tutorial]({{< ref "tutorial/installing-python-with-conda.md" >}}).
