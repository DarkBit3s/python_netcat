# python_netcat
This is a simple python netcat builder to get a reverse shell from a client.
Netcat is the utility knife of networking, so it’s no surprise that shrewd systems administrators remove it from their systems.
In these cases, it’s useful to create a simple network client
and server that you can use to push files, or to have a listener that gives you
command-line access. If you’ve broken in through a web application, it is
definitely worth dropping a Python callback to give you secondary access
without having to first burn one of your trojans or backdoors.

To run this you have to python 2.7 install on your system.If you are running this on Linux simply by running 
**python netcat.py -pera **

and if you run this on window run this as 
**python2 netcat.py -pera**

Python modules used for this exercise is 
"SYS,Socket, Getopt, Threading, Subprocess".

so you have to manully install all these library fro pip.

We begin by reading in all of the command-line options and setting the necessary variables depending on the options we detect.
If you run this with first time and you have no idea how to use it, simply write python and filename. It shows you useful usage information.



