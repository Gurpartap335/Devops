Terminal emulator : is a software application that replicates the functionalities of classic computer terminals .
Shell ::: What is shell ?
>>>  The shell is basically a program that takes your commands from the keyboard
 and sends them to the operating system to perform .

Terminal or console these are just the programs that launch a shell for you .

shell : Bash (Bourne Again shell)
defualt shell : bash
other shells : ksh , zsh , tsch

For checking which shell you are using 
command : ps -p $$ or echo "$SHELL"
For checking number of shells : cat /etc/shells

$ : is just a sign of the shell prompt , means that shell is ready to accept commands . 

Everything in linux is a file .

cd . current
cd .. parent (takes you to the directory above your current)
cd - previous
cd ~ home

file command

less command : opposite of more .
can read file 

Environment variable : 
This is not a linux exclusice thing . It works (almost) the same in windows .

Variable = something that changes
Environment = everything around you

environment variable = a variable that applies to everything around it (aka the shell/terminal/command line)

Type "set" to see all current environment variables

The PATH is a list of directories to check for a command you type

Everytime you type a command without providing the full file name, it'll search the directories 
in your PATH variable for that executable and execute if it's there, otherwise it'll tell you "command not found"