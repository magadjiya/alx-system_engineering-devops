# 0x02. Shell, I/O Redirections and filters

This project touches aspects of shell redirection, and how to manipulate certain commands.

## Table of contents

- [Overview](#overview)
  - [Completed tasks](#completed-tasks)
  - [Links to task files](#links-to-task-files)
- [Mandatory tasks](#mandatory-tasks)
  - [Task 0](#task-0)
  - [Task 1](#task-1)
  - [Task 2](#task-2)
  - [Task 3](#task-3)
  - [Task 4](#task-4)
  - [Task 5](#task-5)
  - [Task 6](#task-6)
  - [Task 7](#task-7)
- [Advanced tasks](#advanced-tasks)
  - [Task 8](#task-8)
  - [Task 9](#task-9)
  - [Task 10](#task-10)
  - [Task 11](#task-11)
  - [Task 12](#task-12)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgements)
- [Credits](#credits)
- [Link to template](#link-to-template)

## Overview

### Completed tasks

- [x] task 0
- [x] task 1
- [x] task 2
- [x] task 3
- [x] task 4
- [x] task 5
- [x] task 6
- [x] task 7
- [x] task 8
- [x] task 9
- [x] task 10
- [x] task 11
- [x] task 12
- [x] task 13
- [x] task 14
- [x] task 14
- [x] task 16
- [x] task 17
- [x] task 18
- [x] task 19
- [x] task 20
- [x] task 21
- [ ] task 22
- [x] task 23
- [x] task 24
- [x] task 25
- [x] task 26


### Links to task files

- **Mandatory tasks**
  - [Task 0][Task 0]
  - [Task 1][Task 1]
  - [Task 2][Task 2]
  - [Task 3][Task 3]
  - [Task 4][Task 4]
  - [Task 5][Task 5]
  - [Task 6][Task 6]
  - [Task 7][Task 7]
  - [Task 8][Task 8]
  - [Task 9][Task 9]
  - [Task 10][Task 10]
  - [Task 11][Task 11]
  - [Task 12][Task 12]
  - [Task 13][Task 13]
  - [Task 14][Task 14]
  - [Task 15][Task 15]
  - [Task 16][Task 16]
  - [Task 17][Task 17]
  - [Task 18][Task 18]
  - [Task 19][Task 19]
  - [Task 20][Task 20]
  - [Task 21][Task 21]
  - [Task 22][Task 22]

- **Advanced tasks**
  - [Task 23][Task 23]
  - [Task 24][Task 24]
  - [Task 25][Task 25]
  - [Task 26][Task 26]

[Task 0]: ./0-hello_world
[Task 1]: ./1-confused_smiley
[Task 2]: ./2-hellofile
[Task 3]: ./3-twofiles
[Task 4]: ./4-lastlines
[Task 5]: ./5-firstlines
[Task 6]: ./6-third_line
[Task 7]: ./7-file
[Task 8]: ./8-cwd_state
[Task 9]: ./9-duplicate_last_line
[Task 10]: ./10-no_more_js
[Task 11]: ./11-directories
[Task 12]: ./12-newest_files
[Task 13]: ./13-unique
[Task 14]: ./14-findthatword
[Task 15]: ./15-countthatword
[Task 16]: ./16-whatsnext
[Task 17]: ./17-hidethisword
[Task 18]: ./18-letteronly
[Task 19]: ./19-AZ
[Task 20]: ./20-hiago
[Task 21]: ./21-reverse
[Task 22]: ./22-users_and_homes
[Task 23]: ./100-empty_casks
[Task 24]: ./101-gifs
[Task 25]: ./102-acrostic
[Task 26]: ./103-the_biggest_fan


## Mandatory tasks

### Task 0
cript that prints "Hello, World to standard output. End with a new line.

**Task file:** [0-hello\_world][Task 0]

### Task 1
A script that displays a confused smiley "(Ôo)'

**Task file:** [1-confused\_smiley][Task 1]

### Task 2
Show content of the /etc/passwd file.

**Task file:** [2-hellofile][Task 2]

### Task 3
Show the contents of /etc/passwd and /etc/hosts.

**Task file:** [3-twofiles][Task 3]

### Task 4
Show last ten lines of /etc/passwd.

**Task file:** [4-lastlines][Task 4]

### Task 5
Show first ten lines of /etc/passwd.

**Task file:** [5-firstlines][Task 5]

### Task 6
Display third line of the file iacta. Using sed is not allowed.

**Task file:** [6-third\_line][Task 6]

### Task 7
A script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

**Task file:** [7-file][Task 7]

### Task 8
Sipt that writes into the file ls\_cwd\_content the result of the command ls -la. If the file already exists, it should be overwritten, else created.

**Task file:** [8-cwd\_state][Task 8]

### Task 9
Duplicate (shell script) the last line of iacta.

**Task file:** [9-duplicate\_last\_line][Task 9]

### Task 10
Delete all .js files in current directory and its subfolders.

**Task file:** [10-no\_more\_js][Task 10]

### Task 11
Count all subdirectories (including hidden ones) in current directory.

**Task file:** [11-directories][Task 11]

### Task 12
Sort and display the ten newest files in the current directory.

**Task file:** [12-newest\_files][Task 12]

### Task 13
A script that takes a list of words as input and prints only words that appear exactly once.
- Input format: One line, one word
- Output format: One line, one word
- Words should be sorted

**Task file:** [13-unique][Task 13]

### Task 14
Show lines containing "root" in /etc/passwd.

**Task file:** [14-findthatword][Task 14]

### Task 15
Show number of lines containing "bin" in /etc/passwd.

**Task file:** [15-countthatword][Task 15]

### Task 16
Show lines containing “root” and 3 lines after them in the file /etc/passwd.

**Task file:** [16-whatsnext][Task 16]

### Task 17
Show all the lines in the file /etc/passwd that do not contain “bin”.

**Task file:** [17-hidethisword][Task 17]

### Task 18
Show all lines of the file /etc/ssh/sshd\_config starting with a capital or small letter.

**Task file:** [18-letteronly][Task 18]

### Task 19
Replace all characters A and c from input to Z and e respectively.

**Task file:** [19-AZ][Task 19]

### Task 20
Shell script that removes all letters c and C from input.

**Task file:** [20-hiago][Task 20]

### Task 21
Shell script that reverse its input.

**Task file:** [21-reverse][Task 21]

### Task 22
Write a script that displays all users and their home directories, sorted by users.
- Based on the the /etc/passwd file

**Task file:** [22-users\_and\_homes][Task 22]

## Advanced tasks

### Task 23
A command that finds all empty files and directories in the current directory and all sub-directories. You are not allowed to use basename, grep, egrep, fgrep or rgrep
- Ony names are displayed, not paths.
- Hidden files should be listed
- One file name per line
- The listing should end with a new line

**Task file:** [100-empty\_casks][Task 23]

### Task 24
script that lists all the files with a .gif extension in the current directory and all its sub-directories.
- Hidden files should be listed
- Only regular files (not directories) should be listed
- The names of the files should be displayed without their extensions
- The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
- One file name per line
- The listing should end with a new line
- You are not allowed to use basename, grep, egrep, fgrep or rgrep

**Task file:** [101-gifs][Task 24]

### Task 25
A script that decodes acrostics that use the first letter of each line.
- The ‘decoded’ message has to end with a new line
- You are not allowed to use grep, egrep, fgrep or rgrep

**Task file:** [102-acrostic][Task 25]

### Task 26
A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
- Order by number of requests, most active host or IP at the top
- You are not allowed to use grep, egrep, fgrep or rgrep

**Task file:** [103-the\_biggest\_fan][Task 26]


## My process

### Built with

- Shell

### What I learned

- I learned about grep, this is particularly useful for spotting patterns.
- tr, how this means translate, it can be used to delete or change specific characters.


## Author

- ALX - [ALX Africa](https://www.alxafrica.com)
- Twitter - [@k\_danhassan](https://twitter.com/yourusername)

## Acknowledgements

Thanks to Evil Ghost for helping me with this template...(Replace this paragraph with yours)  
- Twitter - [@Evil\_Ghost\_\_](https://www.twitter.com/evil_ghost__)

**Note: Acknowledge the people who helped you during the project. You can include their names and also link to their social profiles. Remove or edit the Twitter link above. Delete this note after.**

## Credits

This template is made possible and written by:
- GitHub - [Evil-Ghost](https://github.com/Evil-Ghost)
- Twitter - [@Evil\_Ghost\_\_](https://www.twitter.com/evil_ghost__)
- Medium - [Evil Ghost](https://medium.com/@evilghost)
- Website - [Coming soon...](#)

**Note: Do not remove this if you used this template**

## Link to template

- GitHub Repository - [alx-readme-template](https://github.com/Evil-Ghost/alx-readme-template)

**Note: Do not remove this if you used this template**
