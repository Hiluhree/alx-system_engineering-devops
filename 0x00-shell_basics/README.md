# 0x00 Shell Basics</br>
## Resources</br>
+ [What Is “The Shell”?](http://linuxcommand.org/lc3_lts0010.php)
+ [Navigation](http://linuxcommand.org/lc3_lts0020.php)
+ [Looking Around](http://linuxcommand.org/lc3_lts0030.php)
+ [A Guided Tour](http://linuxcommand.org/lc3_lts0040.php)
+ [Manipulating Files](http://linuxcommand.org/lc3_lts0050.php)
+ [Working With Commands](http://linuxcommand.org/lc3_lts0060.php)
+ [Reading Man pages](http://linuxcommand.org/lc3_man_pages/man1.html)
+ [Keyboard shortcuts for Bash](https://www.howtogeek.com/181/keyboard-shortcuts-for-bash-command-shell-for-ubuntu-debian-suse-redhat-linux-etc/)
+ [LTS](https://wiki.ubuntu.com/LTS)
+ [Shebang](https://en.wikipedia.org/wiki/Shebang_%28Unix%29)
# Tasks </b>
Task 0: [Where am I?](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/0-current_working_directory): A script that prints the absolute path of the current working directory.</br>
Task 1: [What’s in there?](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/1-listit) A script that displays the contents of your current directory. </br>
Task 2: [There is no place like home](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/2-bring_me_home): A script that changes the working directory to the user's home directory.</br>
Task 3: [The long format](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/3-listfiles): A script that displays the current directory contents in a long format.</br>
Task 4: [Hidden files](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/4-listmorefiles): A script that displays the current directory contents including hidden files.</br>
Task 5: [I love numbers](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/5-listfilesdigitonly): A script that displays the current directory contents, using long format, while displaying group IDs in numeral and show hidden files.</br>
Task 6: [Welcome](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/6-firstdirectory): A script that will create a directory named my_first_directory in the /tmp/ directory.</br>
Task 7: [Betty in my first directory](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/7-movethatfile): A script that will move a file called betty from home to the new directory created above.</br>
Task 8: [Bye bye Betty](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/8-firstdelete): A script that will delete file betty from the new location.</br>
Task 9: [Bye bye My first directory](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/9-firstdirdeletion): A script that will delete the directory my_first_directory that is in the /tmp/ directory path.</br>
Task 10: [Back to the future](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/10-back): A script that will Change working directory to the previous one.</br>
Task 11: [Lists](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/11-lists): A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.</br>
Task 12: [File type](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/12-file_type): A script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.</br>
Task 13: [We are symbols, and inhabit symbols](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/13-symbolic_link): A script that Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.</br>
Task 14: [Copy HTML files](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/14-copy_html): A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.</br>
Task 15: [Let’s move](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/100-lets_move): A script that moves all files beginning with an uppercase letter to the directory /tmp/u.</br>
Task 16: [Clean Emacs](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/101-clean_emacs): A script that deletes all files in the current working directory that end with the character ~.</br>
Task 17: [Tree](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/102-tree): A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.</br>
Task 18: [Life is a series of commas, not periods](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/103-commas): A command that lists all the files and directories of the current directory, separated by commas (,).

            1. Directory names should end with a slash (/)
            2. Files and directories starting with a dot (.) should be listed
            3. The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
            4. Only digits and letters are used to sort; Digits should come first
            5. You can assume that all the files we will test with will have at least one letter or one digit
            6. The listing should end with a new line </br>
Task 19: [File type: School](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x00-shell_basics/school): A script to Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.</br>
