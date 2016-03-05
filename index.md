---
layout: page
title: The Unix Shell
---
The Unix shell has been around longer than most of its users have been alive.
It has survived so long because it's a power tool
that allows people to do complex things with just a few keystrokes.
More importantly,
it helps them combine existing programs in new ways
and automate repetitive tasks
so that they don't have to type the same things over and over again.
Use of the shell is fundamental to using a wide range of other powerful tools 
and computing resources (including "high-performance computing" supercomputers).
These lessons will start you on a path towards using these resources effectively.

> ## Prerequisites {.prereq}
>
> This lesson guides you through the basics of file systems and the
> shell.  If you have stored files on a computer at all and recognize
> the word “file” and either “directory” or “folder” (two common words
> for the same thing), you're ready for this lesson.
>
> If you're already comfortable manipulating files and directories,
> searching for files with `grep` and `find`, and writing simple loops
> and scripts, you probably won't learn much from this lesson.

> ## Getting ready {.getready}
>
> For this lesson we will be using the shell on the SHARCNET supercomputer
> `angel.sharcnet.ca`.  To connect you will need a secure shell (SSH)
> program.  Both MacOSX and Linux come with SSH.  For these systems open
> up a terminal and ssh to `angel.sharcnet.ca` using your assigned
> `labXX` account (where *XX* is the lab number you were assigned).
>
> ~~~ {.input}
> $ ssh labXX@angel.sharcnet.ca
> ~~~
>
> For windows you have to first download a SSH program
>
> 1. [MobaXterm](http://mobaxterm.mobatek.net/download.html) or
> 2. [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)
>    and [WinSCP](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html).
>
> Then open it up and enter `angel.sharcnet.ca` as the host to connect
> to, `labXX` as the username, and press `Connect`.
>
> In the following lessons `/User/nelle` (the location of our
> fictitious user Nello Nemo's home directory) with `/home/labXX` (the
> location of your assigned lab account's home directory).


## Topics

1.  [Introducing the Shell](00-intro.html)
2.  [Files and Directories](01-filedir.html)
3.  [Creating Things](02-create.html)
4.  [Pipes and Filters](03-pipefilter.html)
5.  [Loops](04-loop.html)
6.  [Shell Scripts](05-script.html)
7.  [Finding Things](06-find.html)

## Other Resources

*   [Reference](reference.html)
*   [Discussion](discussion.html)
*   [Instructor's Guide](instructors.html)
