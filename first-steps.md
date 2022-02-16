# First steps

Markdown Basics
- Go to [Ccheckbox lists](#checkbox-lists)
- Go to [Links in markdown](#links-in-markdown)
- Go to [Organizing your projects with the terminal](#organizing-your-projects-with-the-terminal)

## Lists

- pretty
- simple
- need a new coffee

## Checkbox lists

- [ ] text
- [x] text 2

see issues

## Links in markdown

### Layout

click [this link](https://google.com) to go to google

click [this link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to to find more commands

-further commands will be added later

## Organizing your projects with the terminal

Terminals will help you to organize your projects. As Linux commands are used, an additional program is necessary

- Cmdr, multi tab support, solid base

click [this link](https://cmder.net/)

- Hyper Terminal, more fancy web-app

click [this link](https://hyper.is/)

- Git Bash (recommended)

Since you will need Git quite early in the bootcamp you can also use the Git Bash.

If you want to use Git Bash please download Git for Windows and install it.

Please select Use Git from Git Bash only during installation.

click [this link](https://git-scm.com/download/win)

## What is a terminal?

A terminal, or a console, is windowfor text based management of your system via a shell (command-line interpreter)
- basically you can run text based commands on your system

Terminals can use different shells, so they may look different

### First steps. Basic commands

Where am I?
- just type "pwd"

Example

Inline-style: 
![alt text](https://user-images.githubusercontent.com/99718218/154245637-7f4c6972-1458-45b4-a174-bcfa38170ff7.JPG "example")

Reference-style: 
![alt text][logo]

[logo]: https://user-images.githubusercontent.com/99718218/154245637-7f4c6972-1458-45b4-a174-bcfa38170ff7.JPG "example"

Clear previous commands with "clear"

Command "ls" shows the content of your current location
Command "ls -l" does the same, but more detailed
Command "ls -a" will also display hidden files
Command "ls -a -l" to detailed list including hidden files

### Creating and changing directions with the mkdir and cd commands

Create Folder

"mkdir coding-projects" will create a folder in your current location named "coding-projects"

Change folder

Command "cd coding-projects" will change your location to that file just created

xxx create or delete a file in your current location

Command "touch"

Example: "touch test.md" will create a md file named test

Inline-style: 
![alt text](https://user-images.githubusercontent.com/99718218/154250358-ea2cd408-d863-4bcc-b29a-4c0c82cde7a7.JPG "touch")

Removing files an folders

Command "rm test.md" will remove this file if it exists

Command "rm -rf project-1" will remove a folder

Caution: Files will be removed permanent.

### Create files with content and ,diesplaying them

Command "echo" just displays the upfollowing inputExample

Command "echo Hallo Welt" will show this

![alt text](https://user-images.githubusercontent.com/99718218/154268860-3c79d187-e41f-4a69-b063-23b41ae69ee9.JPG "echo")

With the command "echo Hallo Welt > test.md" will create a .md file which contents the words Hallo Welt

You can display the content by "cat test.md"

![alt text](https://user-images.githubusercontent.com/99718218/154269520-3f575a75-647c-441b-a970-586d1b677f30.JPG "echo-cat")

If you want to create the Hall Welt as a Headline, echo # Hallo Welt will not work, as the # ist considered as a comment. echo "# Hallo Welt" will do the job

![alt text](https://user-images.githubusercontent.com/99718218/154269520-3f575a75-647c-441b-a970-586d1b677f30.JPG "echo-incl-commands")

Also coping contents in a new file is possible this way

![alt text](https://user-images.githubusercontent.com/99718218/154271726-423d4d5d-f490-493b-8e6f-e387f1277ccc.JPG "echo-cat-exprot")

### Moving and copying files with the mv and cp commands

