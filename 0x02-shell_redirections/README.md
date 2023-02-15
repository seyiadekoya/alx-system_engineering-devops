**SCRIPTS INDEX**

1.	[0-hello_world][1]: Writes a script that prints “Hello, World”, followed by a new line to the standard output.

2.	[1-confused_smiley][2]: Writes a script that displays a confused smiley "(Ôo)'.

3.	[2-hellofile][3]: Displays the content of the /etc/passwd file.\

4.	[3-twofiles][4]: Displays the content of /etc/passwd and /etc/hosts

5.	[4-lastlines][5]: Displays the last 10 lines of /etc/passwd

6.	[5-firstlines][6]: Displays the first 10 lines of /etc/passwd

7.	[6-third_line][7]: Writes a script that displays the third line of the file iacta. The file iacta will be in the working directory. You’re not allowed to use sed

8.	[8-cwd_state][8]: Writes a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

9.	[7-file][9]: Writes a shell script that creates a file named exactly **\'"Holberton School"'\*$?********:) containing the text Holberton School ending by a new line.

10.	[9-duplicate_last_line][10]: Writes a script that duplicates the last line of the file iacta The file iacta will be in the working directory

11.	[10-no_more_js][11]: Writes a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

12.	[11-directories][12]: Writes a script that counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account Hidden directories should be counted

13.	[12-newest_files][13]: Creates a script that displays the 10 newest files in the current directory. Requirements: One file per line Sorted from the newest to the oldest

14.	[13-unique][14]: Creates a scripts that takes a list of words as input and prints only words that appear exactly once. Input format: One line, one word Output format: One line, one word Words should be sorted

15.	[14-findthatword][15]: Displays lines containing the pattern “root” from the file /etc/passwd (grep it)

16.	[15-countthatword][16]: Displays the number of lines that contain the pattern “bin” in the file /etc/passwd

17.	[16-whatsnext][17]: Displays lines containing the pattern “root” and 3 lines after them in the file

18.	[17-hidethisword][18]: Displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.

19.	[18-letteronly][19]: Displays all lines of the file /etc/ssh/sshd_config starting with a letter. include capital letters as well

20.	[19-AZ][20]: Replaces all characters A and c from input to Z and e respectively.

21.	[20-hiago][21]: Creates a script that removes all letters c and C from input.

22.	[21-reverse][22]: Writes a script that reverse its input.

23.	[22-users_and_homes][23]: Writes a script that displays all users and their home directories, sorted by users. Based on the the /etc/passwd file

24.	[100-empty_casks][24]: Writes a command that finds all empty files and directories in the current directory and all sub-directories. Only the names of the files and directories should be displayed (not the entire path) Hidden files should be listed One file name per line The listing should end with a new line You are not allowed to use basename, grep, egrep, fgrep or rgrep

25.	[101-gifs][25]: Writes a script that lists all the files with a .gif extension in the current directory and all its sub-directories. Hidden files should be listed Only regular files (not directories) should be listed The names of the files should be displayed without their extensions The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay) One file name per line The listing should end with a new line You are not allowed to use basename, grep, egrep, fgrep or rgrep

26.	[102-acrostic][26]: An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more. Create a script that decodes acrostics that use the first letter of each line. The ‘decoded’ message has to end with a new line You are not allowed to use grep, egrep, fgrep or rgrep

27.	[103-the_biggest_fan][27]: Writes a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests. Order by number of requests, most active host or IP at the top You are not allowed to use grep, egrep, fgrep or rgrep

[1]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world
[2]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley
[3]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile
[4]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles
[5]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines
[6]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines
[7]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line
[8]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file
[9]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state
[10]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line
[11]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js
[12]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories
[13]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files
[14]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique
[15]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword
[16]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/15-countthatword
[17]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/16-whatsnext
[18]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/17-hidethisword
[19]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/18-letteronly
[20]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/19-AZ
[21]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/20-hiago
[22]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/21-reverse
[23]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/22-users_and_homes
[24]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/100-empty_casks
[25]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/101-gifs
[26]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/102-acrostic
[27]: https://github.com/seyiadekoya/alx-system_engineering-devops/blob/master/0x02-shell_redirections/103-the_biggest_fan












