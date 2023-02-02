# Write your first executable bash shell script on windows:
---------------
## Steps:
- Go to your home directory
    - `cd ~` 
- Create and enter the file .sh.
    - vim testshell.sh
- Open the file and add your script.
    - enter the insert mode (click i)
    - first line is the file type: (#!/bin/bash)
    - then enter your script: echo "hello world!"
    - ESC to exit insert mode.
    - to save the file enter: :wq
- Give permission to the file to be executable.
    - chmod 755 testshell.sh
        - `chmod`: a command to set
- Run the file:
    - ./testshell.sh

---------------
## Of course you can use `nano` instead of `vim`, both are text editors. while nano goes `easier` for me.
----------
Notes:
- .bashrc is a script file for the terminal settings.
- .profile is a file for setting env variables.