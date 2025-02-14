# Working with Git and Bash
As part of the course, I worked with basic Bash commands: created, moved and deleted files and folders, edited content, performed searches, worked with processes and APIs. This experience helped me better understand the command line and file management in the terminal.

Below is the example of my work:

[bash1.txt](https://github.com/KseniiaPetrova923/git_bash/blob/main/bash1.txt)

[bash2.txt](https://github.com/KseniiaPetrova923/git_bash/blob/main/bash2.txt) 

## TASK 1.

| Сommand | Main Use: |
|------------|------------|
| Строка 1.1 | Строка 1.2 |
| Строка 2.1 | Строка 2.2 |
|pwd|determine the name of the folder you are in|
|mkdir test1|create a directory inside this folder called test1|
|cd test1|go to test1 folder|
|touch 1.txt 2.txt 3.txt|create file 1,2 and 3 inside test1 directory|
|ls|check the contents of the test1 directory|
|cd ..|go to home directory|
|mkdir test2|create a folder test2 inside a home directory|
|rmdir test2|delete a folder test2|
|rm test1/2.txt|delete file 2 from test1 folder|
|mkdir test3
cd test3
touch 4.txt
touch 5.txt|create a folder in a home directory test3 and add two files|

cd .. 
rm -r test3
mkdir test4
mv test1/1.txt test4 
mv test1/3.txt test4
cd test4
echo "line" >> 1.txt
echo "line" >> 1.txt
echo "line" >> 1.txt
cat 1.txt
echo "line" >> 3.txt
echo "line" >> 3.txt
echo "line" >> 3.txt
cat 1.txt 3.txt
echo "lalala" > 1.txt
