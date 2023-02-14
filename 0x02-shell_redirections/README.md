		***README FOR 0X02_SHELL_REDIRECTIONS***

#######################################################################################.
		
			0. Hello World
*This script that prints “Hello, World”, followed by a new line to the standard output.

#######################################################################################.
			  1. confused smiley

this a script that displays a confused smiley "(Ôo)'.


#######################################################################################.
		       2. Let's display a file

This script  will display the content of the file /etc/passwd.
When modified the script can read a path to directory and idsplay its content

#######################################################################################.
			   3. What about 2?

This script display the con of two paths to a file.
When seperated with a space cat can display the content of two files.
Just need to pass the paths like this: cat /etc/passwd /etc/hosts.
#######################################################################################.
		       4. Last lines of a file.

Display the last 10 lines of /etc/passwd, using tail comand .
With the tail comand reading the last lines of a log is easier.
You can even pass flags to determine the number of lines you want to read.
#######################################################################################.
		5. I'd prefer the first ones actually
Display the first 10 lines of /etc/passwd, using tail comand .
With the tail comand reading the first lines of a file is easier.
You can even pass flags to determine the number of lines you want to read.
#######################################################################################.
			      6. Line #2
This  script that displays the third line of the file "iacta"
Without using sed, there has to be a go around this problem to have a 
solution for it.
First we have to understand that using the head comand witn -n3 will give you the frst 3
lines and then using pipelines on the same line, tail -n1 will give you the last of the 3 lines.
Solution head -n3 /etc/passwd | tail -n1
#######################################################################################
      7. It is a good file that cuts iron without making a noise.

Write a shell script that creates a file named exactly
 \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the
 text Best School ending by a new line.

#######################################################################################
		 8. Save current state of directory.
Write a script that writes into the file ls_cwd_content the result
 of the command ls -la. If the file ls_cwd_content already exists,
 it should be overwritten. If the file ls_cwd_content does not exist, create it.
#######################################################################################.
			9. Duplicate last line.

Write a script that duplicates the last line of the file iacta.
The file iacta will be in the working directory.
#######################################################################################.
			10. No more javascript,
A script that deletes all the regular files (not the directories) with a .js extension.
Those that are present in the current directory and all its subfolders.

#######################################################################################.