## Quiz
1.	What should be outputted to the display when you type echo Hello World?
-	Hello World 
2.	How do I find what directory you are currently in?
-	Pwd
3.	If you are in /home/pete/Pictures and wanted to go to /home/pete, what’s a good shortcut to use?
-	cd ..
4.	What command would you use to see hidden files?
-	ls -a
5.	How do you create a file called myfile?
-	touch myfile
6.	What command can you use to find the file type of a file?
-	file
7.	What's a good way to see the contents of a file?
-	cat
8.	How do you quit out of a less command?
-	q
9.	What is the command to clear the terminal?
-	clear
10.	What flag do you need to specify to copy over a directory? 
-	-r
11.	How do you rename a file called cat to dog?
-	mv cat dog
12.	What command is use to make a directory? 
-	mkdir
13.	How do you remove a file called myfile?
-	rm myfile
14.	What option should I specify for find if I want to search by name?
-	-name
15.	How do you get quick command line help for built-in bash commands?
-	Help
16.	How do you see the manuals for a command?
-	Man
17.	What command can you use to see a small description of a command?
-	whatis
18.	What command is used to make an alias?
-	Alias
19.	How can you exit from the shell?
-	Exit
## Exercises
# 1. Try some other Linux commands and see what they output:

1. $ date
-  Displays the current date and time.
-  The output shows the day, month, date, time, timezone, and year.
2. $ whoami
- Shows the username of the current user running the command.

# 2. Run the cd command without any flags, where does it take you?
- When you run the cd command without any arguments, it takes you to your home directory.

# 3. Run ls with different flags and see the output you receive.

1. ls -R: recursively list directory contents
2. ls -r: reverse order while sorting
3. ls -t: sort by modification time, newest first


# 4. 
1. Create a new file
- $ touch myfile.txt
2. Note the timestamp
- $ ls -l myfile.txt
3. Touch the file and check the timestamp once again
- Notice that the timestamp has been updated to the current time


# 5. Run the file command on a few different directories and files and note the output.
1. myfile.txt: ASCII text
2. /home/vico/Desktop: directory
3. /bin/ls: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 3.2.0, stripped
4. archive.zip: Zip archive data, at least v2.0 to extract
5. photo.jpg: JPEG image data, JFIF standard 1.01, resolution (DPI), 72 x 72

# 6. Run cat on different files and directories. Then try to cat multiple files.
1. $ cat myfile.txt
- For a regular text file, cat simply prints the file contents line by line to the terminal.
2. $ cat /home/vico/Desktop
- cat: /home/vico/Desktop: Is a directory
3. $ cat myfile1.txt myfile2.txt
- Here, cat displays the content of myfile1.txt followed immediately by the content of myfile2.txt.

# 7. Run less on a file, then page up and around the file. Try searching for a specific word. Quickly navigate to the beginning or the end of the file.
