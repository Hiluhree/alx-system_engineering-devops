Shell Redirections</br>
[Task 0: Hello world](): A script that prints “Hello, World”, followed by a new line to the standard output.</br>
[Task 1: Confused smiley](): A script that displays a confused smiley "(Ôo)'.</br>
[Task 2: Let's display a file](): A script to Display the content of the /etc/passwd file.</br>
[Task 3: What about 2?](): A script to Display the content of /etc/passwd and /etc/hosts.</br>
[Task 4: Last lines of a file](): A script to Display the last 10 lines of /etc/passwd</br>
[Task 5: I'd prefer the first ones actually](): A script to Display the first 10 lines of /etc/passwd</br>
[Task 6: Line #2](): A script that displays the third line of the file iacta.</br>
	N/B The file iacta will be in the working directory and you are not allowed to use sed.
</br>
[Task 7: It is a good file that cuts iron without making a noise](): A shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.</br>
	Note: For this challenge, remember to use a single backslash \ to escape special characters and double backslash \\ to escape the backslash itself.
</br>
[Task 8: Save current state of directory](): A script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.</br>
[Task 9: Duplicate last line](): A script that duplicates the last line of the file iacta.</br>
[Task 10: No more javascript](): A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.</br>
[Task 11: Don't just count your directories, make your directories count](): A script that counts the number of directories and sub-directories in the current directory.</br>
	i. The current and parent directories should not be taken into account
	ii. Hidden directories should be counted
		Solution: mindepth 1 ; To exclude root directory
		Others: maxdepth 1 ; To avoid parsing sub directories. (you may need this in future.)

[Task 12: What’s new]():A script that displays the 10 newest files in the current directory.</br>


	Requirements:

	One file per line
	Sorted from the newest to the oldest

[Task 13: Being unique is better than being perfect](): A script that takes a list of words as input and prints only words that appear exactly once.</br>

	Input format: One line, one word
	Output format: One line, one word
	Words should be sorted
[Task 14: It must be in that file](): A script to Display lines containing the pattern “root” from the file /etc/passwd.</br>
[Task 15: Count that word](): A script to Display the number of lines that contain the pattern “bin” in the file /etc/passwd</br>
[Task 16: What's next?](): A script  Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.</br>
	B : This shows the lines before your pattern match.
	A : This shows the lines after your pattern match.
[Task 17: I hate bins](): A script Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.</br>
[Task 18: Letters only please](): A script to Display all lines of the file /etc/ssh/sshd_config starting with a letter.

include capital letters as well </br>
[Task 19: A to Z](): A script to Replace all characters A and c from input to Z and e respectively.</br>
[Task 20: Without C, you would live in hiago](): A script that removes all letters c and C from input.</br>
[Task 21: esreveR](): A script that reverse its input</br>
[Task 22: DJ Cut Killer](): A script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file </br>
[Task 23: Empty casks make the most noise](): A command that finds all empty files and directories in the current directory and all sub-directories.</br>

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep </br>
[Task 24: A gif is worth ten thousand words](): A script that lists all the files with a .gif extension in the current directory and all its sub-directories.</br>

Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep</br>
[Task 25: Acrostic](): An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. [Read more](https://en.wikipedia.org/wiki/Acrostic).

Create a script that decodes acrostics that use the first letter of each line.

The ‘decoded’ message has to end with a new line
You are not allowed to use grep, egrep, fgrep or rgrep </br>
[Task 26: The biggest fan]():  A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep
