# Linux

### Linux 

<details>
<summary>About Linux</summary><br><b>

</b></details>

<details>
<summary> File & Directory Management Commands and there UseCase:

* ls: List directory contents—view files and directories.
* cd: Change the current directory—navigate the filesystem.
* pwd: Print working directory—show where you are in the filesystem.
* mkdir: Make directory—create new folders.
* rm: Remove files or directories—delete items.
* cp: Copy files or directories—duplicate items.
* mv: Move or rename files or directories—relocate or rename.
* touch: Create empty files or update timestamps—initialize files.
* find: Search for files/directories—locate items by name or attributes.
* grep: Search text using patterns—find lines in files matching a pattern.
* chmod: Change mode (permissions)—set file access rights
* chown: Change owner—assign file ownership.
* zip/unzip: Compress/uncompress ZIP files.
* gzip/gunzip: Compress/uncompress GZIP files.
* df: Disk filesystem usage—show disk space.
* du: Disk usage—show directory size.
* tar: Archive files—create/extract tarballs.
* ln: Create links—make hard or symbolic (soft) links.


</summary><br><b>
</b></details>

<details>
<summary>cd commands and useCases
 
  * cd / -> change to the root directory if present from any location
  * cd ~ -> change to your home directory of user 
  * cd -> change to your home directory
  * cd .. -> change to the directory to Parent directory (Move back to previous directory)
  * cd . -> change to the directory you currently in
  * cd - -> change to the last visited path
  * cd /directoryname -> Move to directory name
    
</summary>
</details>

<details>
<summary>ls commands and useCases

* ls: List directory contents—view files and directories in the current directory.
* ls -l: Display files and directories in long format—shows permissions, owner, size, and modification date.
* ls -a: Show all files, including hidden ones (those starting with a dot).
* ls -la: Combine above—list all files (including hidden) in long format.
* ls -lh: Long format with human-readable file sizes (e.g., KB, MB).
* ls -t: Sort by modification time, newest first.
* ls -r: Reverse the order of the sort (e.g., oldest first, smallest first).
* ls -S: Sort by file size, largest first.
* ls -R: List contents recursively—include all subdirectories.
* ls -d: List directories themselves, not their contents.
* ls -i: Show inode numbers (useful for advanced file operations).
* ls -F: Append indicator characters (e.g., `/` for directories, `*` for executables).
* ls -m: Separate entries with commas.
* ls -Q: Enclose names in quotation marks.
* ls -X: Sort by extension.
* ls -n: Display numeric user and group IDs instead of names.
* ls -g: Long format, but omit owner (show group only).
* ls -ls: Long format, including file size in blocks.
* ls --color: Colorize the output to distinguish file types.
* ls *.txt: List only files with the .txt extension (wildcard filtering).
* ls ~: List contents of the user’s home directory.
* ls /path/to/dir: List contents of a specific directory.
* ls ..: List contents of the parent directory.
* ls -d */: List only directories in the current directory.
* ls -d $PWD/*: List files and directories with full (absolute) paths.
* ls > out.txt: Redirect listing to a file.
* ls -ltr: Frequently used in scripts/logs—lists by time, reverse order, long format (useful for finding recent files).
* ls -R: Essential for examining complex directory trees (e.g., application source, configuration files, logs).
* ls -lh: Important for reviewing disk usage and large files in a readable format.
* ls -a: Critical for revealing hidden configuration files (common in application and system configs).
* ls -ltr *.log: List the most recent log files, long format, sorted by time.
</summary>
</details>
