[Home](README.md)

# Learning Journal Notes: The Coder's Computer

## Cheat Sheet for basic terminal usage
```
   * ls = list contents of current directory
   * ls [options] [location] 
   * ls -l = listing long
   * ls /etc = list contents of current directory (?)
   * ls -l /etc = long list of contents of current directory
   * ls -a = list contents of a directory including hidden files
   * pwd = print working directory
   * file = display file type for a file or directory
   * Absolute paths specify a location relative to root directory (begin with slash ( / ))
   * Relative paths specify a location relative to current directory (do not begin with slash)
   * ~ (tilde) Shortcut for home directory 
      (e.g. for home directory /home/ashley, /home/ashley/Documents can be represented by ~/Documents)
   * . (dot) Reference to current directory ./Documents
   * .. (dotdot) Reference to parent directory (ls ../../ for listing of root directory /home/ashley)
```

## Choosing a Text Editor
There are three basic types of text editors that can be used to create code - basic text editor already installed on most computers, third party text editors, and integrated development environments (IDE). 

### Basic text editor, comes with computer (Text Edit, Notepad, Gedit, etc.) 
Basic / bare-bones editors are just that, basic text editors with no special features.

### Third party text editors (Such as Notepad ++, Text Wrangler, Visual Studio Code, Atom, Brackets, Sublime Text)
These text editors come with many or all of the following handy features to make text editing faster and easier:
   1. Code completion
   2. Syntax highlighting
   3. A nice variety of themes (to reduce eye strain and fatigue)
   4. The ability to choose from a healthy selection of extensions
   5. Live preview
   6. Online community

### Integrated Development Environment (IDE) (Atom, VIM, Sublime Text, Emacs, Komodo Edit)
Software suite containing text editor, file manager, compiler, debugger. Think of an IDE like Microsoft Office that contains Word, Excel, Outlook, Project, and others that all work together.

## Getting Started Using the Terminal

### The Command Line
The command line, also called terminal, is where you enter commands. After the command, you can enter options which modify behavior of the command (typically start with dash ( - ) and/or command line arguments.

Open a terminal in Linux using Applications -> System or Applications -> Utilities. Or right-click and select Open in terminal.

Shell defines how your terminal behaves and looks after running commands, common shell is bash. Check which shell by using command 'echo $SHELL'.

Commands are stored in history, scroll through using up and down arrow keys, go left and right using arrows to edit these commands. Hit tab to complete the command (Tab Completion).

### Basic Navigation
Where are we? pwd = print working directory

What’s in our current location? ls = list

Absolute paths specify a location relative to root directory (begin with slash ( / ))


Relative paths specify a location relative to current directory (do not begin with slash)

Let’s move! cd [location] = change directory

### About Files
Everything is a file.

Linux is an extensionless system - .exe, .txt, .doc - it ignores the extension and looks inside the file to determine what type of file it is. To determine what type of file is at a particular location use command file [path].

Linux is case sensitive (remember for file names, commands, etc.!) Spaces in file names are allowed but in command lines can use quotes (‘Holiday Photos’, treats anything inside quotes as single item) or escape character backslash (Holiday\ Photos, escapes special meaning of next character).

Hidden files and directories begin with a . (full stop). To hide/unhide just rename the file to add/remove the . To list hidden files use command line option -a.
