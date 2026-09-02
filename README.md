## Lab 01

- Name: Hunter Casey
- Email: casey.69@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [hcasey118's GitHub Profile] https://github.com/hcasey118

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |Displays command documentation|
| Get-Location | pwd    |Displays current directory you are in|
| Get-ChildItem | ls    |Lists items in current directory|
| mkdir   | mkdir       |Makes a new directory|
| Set-Location | cd     |Changes your current directory|
| New-Item | touch      |Creates a new file|
| Move-Item | mv        |Moves OR renames a file/directory|
| Copy-Item | cp        |Copies a file/directory|
| Remove-Item | rm      |Deletes a file|
| notepad.exe | vim     |Opens a text editor depending on your system|

## Part 3 - Command Line Navigation

My OS is:
- Ubuntu Linux (WSL)

My Command Line Shell is: Bash

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory:
     /home/hmcasubuntu
2. Create a directory named `DirA`: 
    mkdir DirA
3. Create a directory named `Dir B`: 
    mkdir DirB
4. Go into `DirA`: 
    cd DirA
5. Go into `Dir B` from `DirA`:
    cd ../DirB ***
6. Return to your user's home directory:
    cd
7. Create a file named `test.txt`:
    touch test.txt 
8. Move the file named `test.txt` into `DirA`:
    mv test.txt DirA
9. Contents of `test.txt`: (vim test.txt) ***
```
Testing "test.txt". This is a test.
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`:
    cp test.txt copy.txt
11. View the contents of `DirA`: 
    ls
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:
    cp test.txt ../DirB
    cd ../DirB
    mv test.txt fodder.txt
13. Delete / remove both `fodder.txt` AND `Dir B`:
    cd .. (to get to parent directory from DirB)
    rm -r DirB



## Citations

Used ChatGPT to find commands to work within Vim and to move from DirA to DirB (".." refers to parent directory). Noted with "***"

"unix.stackexchange.com" used to find how to delete a directory and its contents:
    "rmdir" to delete an empty directory (DirB is not empty so this will throw an error)
    "rm -r" removes directory and its contents

Vim commands: 
    "i" to insert/edit text
    "Escape Key" to get out of the edit mode ("i")
    ":w" to write the changes to the file or ":wq" to write and quit immediately
    ":q!" to quit without saving




