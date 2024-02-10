AirBnB_clone | The console


Description of the project

This project is just a simple copy of the AirBnB website. The AirBnB console is about creating a minishell, this console works in interactive and non-interactive mode.


Description of the command interpreter

The command interpreter is also the command shell or simply a shell. The first piece is to manipulate a powerful storage system. This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”. This means: from your console code (the command interpreter itself) and from the front-end and RestAPI you will build later, you won’t have to pay attention (take care) of how your objects are stored.


How to start it:

In order to start the console, you must use the following command:
./console.py


How to use it:

manage (create, update, destroy, etc) objects via a console / command interprete
store and persist objects to a file (JSON file)
Commands: create, show, destroy, all (shows all), update, help, quit.


Examples:

Your shell should work like this in interactive mode:
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$


But also in non-interactive mode: (like the Shell project in C)

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
