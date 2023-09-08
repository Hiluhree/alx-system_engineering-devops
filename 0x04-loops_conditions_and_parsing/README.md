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
