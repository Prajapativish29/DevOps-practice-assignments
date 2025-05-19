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


 #Python Assignments
 1. Grade Checker
A simple program that takes a score as input and prints the grade based on the following criteria:

90+ → Grade A

80–89 → Grade B

70–79 → Grade C

60–69 → Grade D

Below 60 → Grade F

Concepts used: if-else statements

2. Student Grades
A dictionary-based program that allows the user to:

Add a new student and their grade

Update an existing student's grade

Print all student grades

Concepts used: dictionary, if-else, basic user input and update operations

 3. Write to a File
Created a text file and wrote some content into it using:

open() in write mode ("w")

write() function

Concepts used: File handling — writing data to a file

 4. Read from a File
Opened a text file in read mode and printed its contents using:

open() in read mode ("r")

read() function

Concepts used: File handling — reading data from a file
