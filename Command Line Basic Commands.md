The command line is a tool for interacting with a computer using only text (also known as a text interface) rather than other methods like clicking and scrolling. 
Essential for developing websites and applications!
UNIX command is a type of command that is used in Linux and macOS.

--- Getting Started ---

1. Creating files:
You can create an empty file by 'touch' command.
    
        $touch file_name
    
2. Displaying a File:
You can also display the content of a file with the 'cat' command.
    
        $cat file_name
    
3. Creating a Directory:
You can create a new directory using 'mkdir' command.
(A directory is commonly used interchangeably with the term folder.)
    
        $mkdir directory_name
    
--- File Structures ---
    
4. Moving Between Directories
You can use the 'cd' command to move to other directories.
    
        $cd directory_name
    
5. Checking the Current Directory
(The root directory is represented by /)
When you execute the 'pwd' command, all directories from the root directory to the current directory are displayed.
    
        $pwd
    
6. Displaying a list of files
This can be done using the 'ls' command.
(Note that the ls command will only display the directories and files that are direct children of the current directory.)
    
        $ls
    
7. The Parent Directory
If you want to move to the parent directory, you can use a special symbol .., like cd ..
    
        $cd ..
    
8. The Home Directory
To move to home directory use 'cd' command.
    
        $cd
    
Handling Files and folders
    
9. Moving Files and Directories
Let's start with the command to move a file.
To do this, we use the 'mv' command.
(you can move a file to the specified directory.)
    
        $mv file_to_move destination_directory
    
10. Renaming files and directories
The 'mv' command, can also be used to rename a file.
    
        $mv old_file_name new_file_name
    
11. Copying Files and Directories
Copying a File
We use the 'cp' command.
    
        $cp file_to_copy new_file_name
    
copying a directory
    
        $cp -r directory_to_copy new_directory_name
    
12. Removing files and sirectories
To do this, you can use the 'rm' command.
to remove a file:
    
        $rm file_to_remove
    
to remove a directory
    
        $rm -r directory_to_remove
