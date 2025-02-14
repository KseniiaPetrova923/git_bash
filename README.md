# Working with Git and Bash
As part of the course, I worked with basic Bash commands: created, moved and deleted files and folders, edited content, performed searches, worked with processes and APIs. This experience helped me better understand the command line and file management in the terminal.

Below is the example of my work:

[bash1.txt](https://github.com/KseniiaPetrova923/git_bash/blob/main/bash1.txt)

[bash2.txt](https://github.com/KseniiaPetrova923/git_bash/blob/main/bash2.txt) 

## TASK 1.

| Сommand | Main Use: |
|------------|------------|
|pwd|determine the name of the folder you are in|
|mkdir test1|create a directory inside this folder called test1|
|cd test1|go to test1 folder|
|touch 1.txt 2.txt 3.txt|create file 1,2 and 3 inside test1 directory|
|ls|check the contents of the test1 directory|
|cd ..|go to home directory|
|mkdir test2|create a folder test2 inside a home directory|
|rmdir test2|delete a folder test2|
|rm test1/2.txt|delete file 2 from test1 folder|
|mkdir test3; cd test3; touch 4.txt; touch 5.txt|create a folder test3 in a home directoryand add two files|
|cd .. ; rm -r test3|delete a folder test3|
|mkdir test4|create a folder test4 inside a home directory|
|mv test1/1.txt test4 ; mv test1/3.txt test4| move files 1 and 3 from test1 folder to test4 folder|
|cd test4; echo "line" >> 1.txt ;echo "line" >> 1.txt ; echo "line" >> 1.txt|add three lines to file 1 with the word "line"|
|cat 1.txt|view contents of file 1|
|echo "line" >> 3.txt ; echo "line" >> 3.txt ; echo "line" >> 3.txt|add three lines to file 3 with the word "line"|
|cat 1.txt 3.txt|view the contents of two files (1 and 3) at once|
|echo "lalala" > 1.txt|Using one of the editors replace all lines in file 1|
