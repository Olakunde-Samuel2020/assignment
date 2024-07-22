Exercises 
Create a file called name.txt. 

Try renaming the file to rename.txt using the mv command. What 
does this tell you about the command?

Using the cp command, make a copy of 
rename.txt and call it 
copy.txt. 

Remove the file copy.txt. 

Create a folder called questions. 

Change directories to the questions folder. 

Create a file called first.txt.

Create a file called second.txt.

Go back a directory and make a copy of 
the questions folder and call it 
questions_copy. 

When using cp -r what is the -r called? What does it do? 

Delete the original questions folder and the copy.


1 New-Item -Path . -Name "name.txt" -ItemType "file"
2 mv name.txt 
3 cp rename.txt copy.txt
4 rm copy.txt
5 mkdir questions
6 cd questions
7 New-item -Path . -Name "first.txt" -ItemType "file"
8New-item -Path . -Name "second.txt" -ItemType "file"
9 cd ..
10 cp -r questions questions_copy
11 -r is a flag and it makes it easy to tag  the folder for copying
12 rm -rf questions but after testing it it didn't need the -rf 
13 rm -rf questions_copy but after testing it it didn't need the -rf 