# Process Killer

It just kills processes as they appear on your computer.\
It uses the name of the executable file as you can see in [processList.txt](./processList.txt).

Currently [processList.txt](./processList.txt) contains a list of things that _were_ running on _my_ computer.\
All the things in there should be running at some point, but that point is not **now**.

\* There are no easter eggs in the source code.

# Features

-   Periodically checks the running processes on your **Windows** PC and forceably kills them based on the **[File Name](#how-to-find-your-process-name-in-task-manager--)** of the running process.

-   You can comment the plain-text list of file names with c-style comments "`//`"

-   Thats it!

# Helpful Info

### How to find _**YOUR**_ process name in Task Manager -

1.  Right click on the running task
    <br/>
    <br/>
2.  Click on the "Properties" item in the right click menu

    -   A window called "`<TASKNAME>.exe Properties`" will raise!
        <br/>
        <br/>

3.  The InputBox at the top of this Window contains the _**FILE NAME**_ we need
    -   The file name is also the name of the window _**MINUS**_ the "`Properties`"
