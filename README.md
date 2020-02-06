# newfile

A script that will create a newfile. If the Script is able to find the Shebang for the file
It will place it at top of the new file and then proceed to ask if you wish to open the file in vim.

# Examples

```
newfile file.sh     # will create a new file called file.sh, If the file already exists it 
                    will ask if you wish to open the program in vim instead
```
```
newfile -c          # will take the file name directly from your clip board
```
```
newfile -f file.sh  # if there is already a file.sh it will delete the previous file
                       and create a blank file
```
```
newfile -v file.sh  # will create the file.sh and open imediately in vim without a prompt
```

for more information on what the program does you can open the man file attatched or type in;
```
newfile -h
```

# Not Working
you will have to have vim and xclip installed to run the script at its current state.
