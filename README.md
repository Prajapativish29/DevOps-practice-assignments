# Linux-command-practice
Linux Command Line Practice
This is a quick summary of basic Linux command line tasks I practiced:

1. Creating and Renaming Files/Directories
Created a directory: mkdir test_dir

Created a file: touch test_dir/example.txt

Renamed file: mv example.txt renamed_example.txt

2. Viewing File Contents
Displayed contents of /etc/passwd: cat /etc/passwd

First 5 lines: head -n 5 /etc/passwd

Last 5 lines: tail -n 5 /etc/passwd

3. Searching for Patterns
Found lines with "root": grep root /etc/passwd

4. Zipping and Unzipping
Compressed directory: zip -r test_dir.zip test_dir

Unzipped into new directory: unzip test_dir.zip -d unzipped_dir

5. Downloading Files
Downloaded a file: wget https://example.com/sample.txt

6. Changing Permissions
Created file: touch secure.txt

Set read-only permissions: chmod 444 secure.txt

7. Environment Variables
Set a variable: export MY_VAR="Hello, Linux!"


