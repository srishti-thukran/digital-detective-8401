## TASK-2.1 Explore basic Terminal operations

| OPERATION | COMMAND NAME | WHAT IT DOES | WHAT I OBSERVED |
|-----------|--------------|--------------|-----------------|
| Current-directory display | pwd | display the full path of the current working directory | It shows the complete location of my current folder |
| Directory listing | ls | lists files and folders in the current location | it displayed the available files and folders|
| detailed listing | ls -l | displays the files with permissions, size and modification date | additional information about each file |
| change directory | cd .. | moves to the parent directory | location changed to the folder one level above |
|create directory | mkdir {folder_name} | creates a new directory/folder | a new folder was created |
|create emptly file | touch {file_name} | creates an empty file | an empty file appeared in the folder |
|copy file | cp {path1} {path2} | creates copy of an existing file | second same file created |
| move/rename file | mv {name1} {name2} | Moves or changes the name of a file | the file was renamed |
| display the file content | cat | Displays the contents of a text file | The text inside original.txt appeared in the Terminal | 

## TASK-2.2 Practice file changes safely

--> Difference between replacing a file's contents and adding text to the end <--
Replacing a file's content means that whatever previous content the file had , is deleted now and the new added text is it's only content .
Adding text to the ends means adding adding text without deleting or any changes made to the previous added content.

--> Difference between copying a file and moving a file <--
when we copy a file it exists in both forms (the original file and the copied file) but when we move a file it only exists at the location we moved it to.

-->Information provided by the current-directory display<--
 It displays the full path of the current working directory

 -->Use of directory-listing operation useful<--
 A directory-listing operation (using the ls command) is useful because it helps us see all the files and folders present in our current directory.

 ## TASK-2.3 Understand flags and pipes

First, I used the `ls` command to display the files and folders in the current directory.
Next, I used `ls -la` to display a detailed listing, including hidden files and human-readable file sizes. The `-l` flag shows detailed information, `-a` includes hidden files .
The normal listing only displays file and folder names, whereas the detailed listing provides additional information such as permissions, ownership, file size and modification date.
After that, I used `ls -la | head`. The pipe symbol (`|`) passes the output of the first command to the second command as input. The `ls -la' command generates the detailed listing, while `head` displays only its first 10 lines.
Thus, pipes allow us to combine commands and process their output efficiently.

## TASK-2.4 Understand package managers

Package managers are useful because they make it easier to install, update, and remove software and libraries. They automatically manage dependencies required by different programs, saving time and reducing manual effort. They also help keep software organised and up to date.

----------------------------------------------------------------------------------------

## 1.Tasks Completed

-->Explored basic Terminal commands.
-->Practised creating, navigating, listing and managing files and directories.
-->Understood Markdown formatting and tables.
-->Learned about command flags and pipes.
-->Understood the usefulness of package managers.

## 2. command names used

pwd- Displays the current working directory.
ls- Lists files and folders.
ls -l- Displays a detailed directory listing.
ls -la- Shows detailed information, including hidden files.
cd- Changes the current directory.
mkdir- Creates a new directory.
mkdir -p- Creates parent and nested directories.
touch- Creates an empty file.
echo- Displays or writes text.
> - Redirects output and overwrites existing file content.
>> - Appends output to the end of a file.
cat- Displays file contents.
head- Displays the first few lines of a file or input.
ls -la | head- Displays the first 10 lines of a detailed directory listing.

## 3. Understanding of file operations, flags and pipes

File operations help us create, access, modify and organise files and directories.
mkdir is used to create directories.
cd helps navigate between directories.
touch creates empty files.
echo can write text into files.
> overwrites existing content, whereas >> appends new content.
cat allows us to view file contents.
These operations help keep files organised and make working with the Terminal easier.

Flags are options added to commands to change their behaviour.
The pipe symbol (|) passes the output of one command as the input of another command.







