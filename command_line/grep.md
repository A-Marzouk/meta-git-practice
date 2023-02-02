# Grep
## global regular expression print
### Used to search across files, folders and files content.

## Examples:
- `grep` ah names.txt: this will search for any word containing the 'ah' value in this files and print it back.
- `grep -i` it will ignore the case sensitivity,  note that grep is case sensitive by default.
- `grep -w` will return exactly the search value, not partial search.
- flags can be added at the end of the command.
- to search in a list of directories, you can combine the `ls` command with `grep` command using pipes `"|"`: 
    - `ls /directory | grep filename`
    - `ls | grep .txt` to get all text files in current directory.

