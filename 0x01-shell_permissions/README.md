# 0x01. Shell, permissions

## Table of contents

 
- [Overview](#overview)
  - [Completed tasks](#completed-tasks)
  - [Links to task files](#links-to-task-files)
- [Mandatory tasks](#mandatory-tasks)
- [Advanced tasks](#advanced-tasks)
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
- [x] task 15
- [x] task 16
- [x] task 17

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

- **Advanced tasks**
  - [Task 14][Task 14]
  - [Task 15][Task 15]
  - [Task 16][Task 16]
  - [Task 17][Task 17]

[Task 0]: ./0-iam_betty
[Task 1]: ./1-who_am_i
[Task 2]: ./2-groups
[Task 3]: ./3-new_owner
[Task 4]: ./4-empty
[Task 5]: ./5-execute
[Task 6]: ./6-multiple_permissions
[Task 7]: ./7-everybody
[Task 8]: ./8-James_Bond
[Task 9]: ./9-John_Doe
[Task 10]: ./10-mirror_permissions
[Task 11]: ./11-directories_permissions
[Task 12]: ./12-directory_permissions
[Task 13]: ./13-change_group
[Task 14]: ./100-change_owner_and_group
[Task 15]: ./101-symbolic_link_permissions
[Task 16]: ./102-if_only
[Task 17]: ./103-Star_Wars

## Mandatory tasks

### Task 0
A script that switches the current user to the user betty.
Use exactly 8 characters for your command (+1 character for the new line)
Assume that the user betty will exist when we will run your script

### Task 1
A script that prints the effective username of the current user.

### Task 2
A script that prints all the groups the current user is part of.

### Task 3
Script that changes the owner of the file hello to the user betty.

### Task 4
Script that creates an empty file called hello.

### Task 5
Script that adds execute permission to the owner of the file hello.
The file hello will be in the working directory

### Task 6
A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
The file hello will be in the working directory

### Task 7
Script that adds execution permission to the owner, the group owner and the other users, to the file hello
The file hello will be in the working directory
You are not allowed to use commas for this script

### Task 8
A script that sets the permission to the file hello as follows:
Owner: no permission at all.
Group: no permission at all.
Other users: all the permissions.
The file hello will be in the working directory. You are not allowed to use commas for this script

### Task 9
Script that sets the mode of the file hello to this:
[-rwxr-x-wx].
The file hello will be in the working directory.
You are not allowed to use commas for this script.

### Task 10
Script that sets the mode of the file hello the same as olleh’s mode.

### Task 11
Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
Regular files should not be changed.

### Task 12
A script that creates a directory called my\_dir with permissions 751 in the working directory.

### Task 13
Script that changes the group owner to school for the file hello


## Advanced tasks

### Task 14
Script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

### Task 15
script that changes the owner and the group owner of \_hello to vincent and staff respectively. \_hello is a symbolic link.

### Task 16
A script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

### Task 17
Play StarWars IV episode in the terminal


## My process

### Built with
Shell


### What I learned
- mkdir has the -m option which allows you to create a directory while simultaneously setting its permissions

## Author

- ALX - [ALX Africa](https://www.alxafrica.com)
- Twitter - [@k\_danhassan](https://twitter.com/k_danhassan)

## Acknowledgements


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
