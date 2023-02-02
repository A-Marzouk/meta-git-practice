# Redirection

## We have 3 standard directions on our system:
- stdin: standard input 0.
- stdout: standard output 1. 
- stderr: standard error 2.

### But we can change that, by accepting an input from the user using the `cat` command:
- `cat` `>` input.txt
    - now you can enter your text input.
    - to finish you press `ctrl + d` to let the `cat` command know it is the end of the file. 
- `>` : Note that this greater than sign `>` is used to control where the output goes. in previous example with `cat` command we made it go to the input.txt file.
    - Ex: to print the output of a command to a file instead of the default direction (stdout) we use the `>` sign: `ls -l > output.txt`
    - if the file doesn't exist, it will be created.

- the standard error (stderr) output can also be written to a file, when using redirection of output we will need to specify the number of type of the output.
    - `2>` for the error output.
    - `2>&1` to combine both outputs standard and error output to one file. you use it this way: 
        - `ls -l` /not-exist `>` logs.txt `2>&1` 
    - To append the data to the file not to overwrite it you can use the `>>` double greater than sign instead of single `>`.