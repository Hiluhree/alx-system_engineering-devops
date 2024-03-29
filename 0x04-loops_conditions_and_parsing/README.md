# 0x04. Loops, conditions and parsing
## Resources

+ [Loops sample](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html)
+ [Variable assignment and arithmetic](https://tldp.org/LDP/abs/html/ops.html)
+ [Comparison operators](https://tldp.org/LDP/abs/html/comparison-ops.html)
+ [File test operators](https://tldp.org/LDP/abs/html/fto.html)
+ [Make your scripts portable](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)

### More Info
#### Shellcheck
+ [Shellcheck](https://github.com/koalaman/shellcheck) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. ``Shellcheck`` is your friend! **All your Bash scripts must pass Shellcheck without any error or you will not get any points on the task.**

``Shellcheck`` is available on the school’s computers. If you want to use it on your own computer, here is how to [install it](https://github.com/koalaman/shellcheck#installing).

## Tasks
### 0. Create a SSH RSA key pair
+ [0-RSA_public_key.pub](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/0-RSA_public_key.pub)
Read for this task:

	+ [Linux and Mac OS users](https://askubuntu.com/questions/61557/how-do-i-set-up-ssh-authentication-keys)
	+ [Windows users](https://docs.rackspace.com/docs/generating-rsa-keys-with-ssh-puttygen)
man: ``ssh-keygen``

You will soon have to manage your own **servers** concept page hosted on remote [data centers](https://www.youtube.com/watch?v=iuqXFC_qIvA&t=46s). We need to set them up with your RSA public key so that you can access them via SSH.

Create a RSA key pair.

Requirements:

	+ Share your **public key** in your answer file ``0-RSA_public_key.pub``
	+ Fill the ``SSH public key`` field of your intranet profile with the public key you just generated
	+ **Keep the private key to yourself in a secure location**, you will use it later to connect to your servers using SSH. Some storing ideas are Dropbox, Google Drive, password manager, USB key. Failing to do so will prevent you to access your servers, which will prevent you from doing your projects
	+ If you decide to add a passphrase to your key, make sure to save this passphrase in a secure location, you will not be able to use your keys without the passphrase
SSH and RSA keys will be covered in depth in a later project.

### 1. For Best School loop
+ [1-for_best_school](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/1-for_best_school): a Bash script that displays ``Best School`` 10 times.

Requirement:

	+ You must use the ``for`` loop (``while`` and ``until`` are forbidden)
Note that:

	+ The first line of my Bash script starts with ``#!/usr/bin/env bash``
	+ The second line of my Bash scripts is a comment explaining what it is doing

### 2. While Best School loop
+ [2-while_best_school](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/2-while_best_school): a Bash script that displays ``Best School`` 10 times.

Requirements:

	+ You must use the ``while`` loop (``for`` and ``until`` are forbidden)

### 3. Until Best School loop
+ [3-until_best_school](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/3-until_best_school): a Bash script that displays ``Best School`` 10 times.

Requirements:

	+ You must use the ``until`` loop (``for`` and ``while`` are forbidden)

### 4. If 9, say Hi!
+ [4-if_9_say_hi](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/4-if_9_say_hi): a Bash script that displays ``Best School`` 10 times, but for the 9th iteration, displays ``Best School`` and then ``Hi`` on a new line.

Requirements:

	+ You must use the ``while`` loop (``for`` and ``until`` are forbidden)
	+ You must use the ``if`` statement

### 5. 4 bad luck, 8 is your chance
+ [5-4_bad_luck_8_is_your_chance](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/5-4_bad_luck_8_is_your_chance): a Bash script that loops from 1 to 10 and:

	+ displays bad luck for the 4th loop iteration
	+ displays good luck for the 8th loop iteration
	+ displays Best School for the other iterations
Requirements:

	+ You must use the ``while`` loop (``for`` and ``until`` are forbidden)
	+ You must use the ``if``, ``elif`` and ``else`` statements

For the most curious:

[8 in the Chinese culture](https://freakonomics.com/)
[4 in the Chinese culture](https://en.wikipedia.org/wiki/Chinese_numerology#Four)

### 6. Superstitious numbers
+ [6-superstitious_numbers](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/6-superstitious_numbers): a Bash script that displays numbers from 1 to 20 and:

	+ displays 4 and then bad luck from China for the 4th loop iteration
	+ displays 9 and then bad luck from Japan for the 9th loop iteration
	+ displays 17 and then bad luck from Italy for the 17th loop iteration
Requirements:

	+ You must use the while loop (for and until are forbidden)
	+ You must use the case statement

### 7. Clock
+ [7-clock](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/7-clock): a Bash script that displays the time for 12 hours and 59 minutes:

	+ display hours from 0 to 12
	+ display minutes from 1 to 59
Requirements:

	+ You must use the ``while`` loop (``for`` and ``until`` are forbidden)
Note that in this example, we only display the first 70 lines using the ``head`` command.

### 8. For ls
+ [8-for_ls](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/8-for_ls): a Bash script that displays:

	+ The content of the current directory
	+ In a list format
	+ Where only the part of the name after the first dash is displayed (refer to the example)
Requirements:

	+ You must use the for loop (while and until are forbidden)
	+ Do not display hidden files

### 9. To file, or not to file
+ [9-to_file_or_not_to_file](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/9-to_file_or_not_to_file): a Bash script that gives you information about the ``school`` file.

Requirements:

+ You must use ``if`` and, ``else`` (case is forbidden)
+ Your Bash script should check if the file exists and print:
	- if the file exists: ``school file exists``
	- if the file does not exist: ``school file does not exist``
+ If the file exists, print:
	- if the file is empty: ``school file is empty``
	- if the file is not empty: ``school file is not empty``
	- if the file is a regular file: ``school is a regular file``
	- if the file is not a regular file: (nothing)
### 10. FizzBuzz
+ [10-fizzbuzz](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/10-fizzbuzz): a Bash script that displays numbers from 1 to 100.

Requirements:

	+ Displays ``FizzBuzz`` when the number is a multiple of 3 and 5
	+ Displays ``Fizz`` when the number is multiple of 3
	+ Displays ``Buzz`` when the number is a multiple of 5
	+ Otherwise, displays the number
	+ In a list format

### 11. Read and cut
+ [100-read_and_cut](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/100-read_and_cut): a Bash script that displays the content of the file ``/etc/passwd``.

Your script should only display:

	+ username
	+ user id
	+ Home directory path for the user
Requirements:

	+ You must use the while loop (for and until are forbidden)

### 12. Tell the story of passwd
+ [101-tell_the_story_of_passwd](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/101-tell_the_story_of_passwd): a Bash script that displays the content of the file ``/etc/passwd``, using the ``while`` loop + IFS.

Format: ``The user USERNAME is part of the GROUP_ID gang, lives in HOME_DIRECTORY and rides COMMAND/SHELL. USER ID's place is protected by the passcode PASSWORD, more info about the user here: USER ID INFO``

Requirements:

	+ You must use the ``while`` loop (``for`` and ``until`` are forbidden)

Read:

[IFS (internal field separator)](https://tldp.org/LDP/abs/html/internalvariables.html)
[Understanding /etc/passwd](https://www.cyberciti.biz/faq/understanding-etcpasswd-file-format/)
The file ``/etc/passwd`` has already been covered in a previous project and you should be familiar with it. Today we will make up a story based on it. 

### 13. Let's parse Apache logs
+ [102-lets_parse_apache_logs](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/102-lets_parse_apache_logs):  a Bash script that displays the visitor IP along with the [HTTP status code](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes) from the Apache log file.

Requirement:

+ Format: IP HTTP_CODE
	+ in a list format
	+ See example
+ You must use ``awk``
+ You are not allowed to use while, for, until and cut
+ Download and commit the apache-access.log file along with your answers files

[Apache](https://en.wikipedia.org/wiki/Apache_HTTP_Server) is among the most popular web servers in the world, serving 50% of all active websites, no doubt that you will have to interact with it within your career.

As a Full-Stack Software Engineer, you have to master the art of parsing log files. Today we will do a simple parsing of Apache log access files.

Today the Customer Support department reported that a user reported that the site is being “buggy”. Not being a detailed description, you want to have a look at the Apache logs and gather data about the traffic.

### 14. Dig the data
+ [103-dig_the-data](https://github.com/Hiluhree/alx-system_engineering-devops/blob/master/0x04-loops_conditions_and_parsing/103-dig_the-data): a Bash script that groups visitors by IP and HTTP status code, and displays this data.

Requirements:

+ The exact format must be:
	- OCCURENCE_NUMBER IP HTTP_CODE
	- In list format
+ Ordered from the greatest to the lowest number of occurrences
	- See example
+ You must use ``awk``
+ You are not allowed to use ``while``, ``for``, ``until`` and ``cut`` 
