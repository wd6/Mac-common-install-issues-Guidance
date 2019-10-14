https://www.taniarascia.com/how-to-create-and-use-bash-scripts/

**A terminal** is a program (command line interface) that runs a shell, which interprets the commands.

### Command Lines
1. ```pwd``` Print Working directory
2. ```ls``` List directory contents
3. ```clear``` Clear the terminal screen
4. ```cd``` Change Directory
5. ```.``` one dot represents the currrent directory;  ```..``` represents one derectory backwards; ```../..``` will take you back for two directories.
6. ```mkdir``` Make Directory. It will create a new folder
7. ```touch``` create new file; create multiple files by ```touch one.txt two.txt three.html```
8. ```echo "Hello World" > hello.txt``` create a 'hello.txt' file with "Hello World" contents
9. ```cat hello.txt``` view the content of a file
10. ```rm```  Remove a file
11. ```*``` repesents wildcard. ```rm *.txt``` will delete all txt file in current directory; ```rm file1 file2``` will remove multiple files
12. ``` rmdir ``` will remove an empty directory; for un-empty directory, use ``` rm -r ``` to remove
13. ```cp source_file destination``` copy source_file to destination.
14. ``` cp -r directory1 directory2 ``` will copy directory1 to directory2
15. ```mv source_file directory``` will move source to directory


16. Running multiple commands: use ``` command1 && command2``` once the first command is successful, the subsequent one will run

17. ```chmod 644 test.html``` will Changing permissions of the file.

18. ```sudo``` stands for Super User Do. It will run the command as administrator 
19. ```sudo su``` will switch you to a administrator user. The terminal will look different

20. Connecting to Another server with ```ssh```(Secure SHell) 

21. Other useful commands:
22. ```whoami``` tells you the user name
23. ```dig website_name``` DNS Lookup, shows the ip and something of the website
24. ```man touch``` (Manual) will show the help guide of ```touch``` command. Press ```q``` to exit the manual page

25. A basic text editor. ```nano file_name``` will open a file and edit it

