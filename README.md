# Mini_Project-Basic-Linux-Commands

## This implementation focuses on hands-on practice with basic Linux commands.
### The basic tools used for this project are:
- GitBash
- GitHub and
- Visual Studeo code as well as Markdown for documentation

## Below are the screenshots demonstrating various basic commands:

### Manipulating files and Directories on Linux
- The `sudo` command: `sudo` stand for `superuser do,` and it allows you to run commands with the security privileges of another user, typically the superuser or `root`.

### 1. Creating a folder with `sudo`
![sudo command to create folder in the root](./img/3.sudoCommandtocreatefolder.png)

## pwd Command: Used to find the path of your current working directory

![pwd command](./img/4.pwd.png)

Linux Directory Structure

The Root Directory `("/")`

At the top of the Linux filesystem hierarchy is the root directory, denoted by a single slash `/`. Unlike Windows, which uses different drives `(C:, D:, etc.)`, Linux organizes everything starting from this root directory. Under `/`, you'll find various directories with specific purposes:

- `/bin`: Essential user command binaries (programs) that need to be available to all users are stored here (e.g., ls, cp).
- `/etc`: Configuration files for the system can be found in here.
- `/home`: Personal directories for users.
- `/root`: The home directory for the root user.
- `/var`: Variable data like logs.
- `/usr`: Secondary hierarchy for user data; contains majority of user utilities and applications.

### 2. `cd` Command: Used to navigate through the Linux files and directories.

![](./img/5.cd.png)

### To list the files and directories on the root file system

![](./img/6.listsudofiles.png)

## My Side Hustle Task 1:
1. Create a directory called `photos` inside the `usr` directory

![](./img/6.photo-sinside-usr.png)

2. Navigate into the `photos` directory

![](./img/7.navigate-into-photos.png)

3. Create 3 more random directories inside the `photos` directory

![](./img/8.randomfolders.png)

4. Show the newly created directories on the terminal

![](./img/9.showtherandomfolders.png)

5. Navigate into one of them

![](./img/10.tradpics.png)

6. Show the full path where you currently are on the screen

![](./img/11.fullpath.png)

### `ls` Command: Used to list files and directories
To view files in the Document Directory
![](./img/12.ls.png)

### Some options that can be used with the `ls` command
- `ls -R` Lists all the files in the subdirectories.

![](./img/13.LS-R.png)

- `ls -a` shows hidden files in addition to the visible ones.

![](./img/14.ls-a.png)

- `ls -lh` shows the file sizes in easily readable formats, such as MB, GB, and TB.

![](./img/15.ls-lh.png)

### `cat` Command: `Concatenate`, or `cat`, is used to list, combine and write file content to the standard output.

![](./img/16.catcommand.png)

Display the content of `os-release` file in the `/etc/` directory

### `cp` Command: Used to copy files or directories and their content.

![](./img/17.cptodocuments.png)

### `cp` Command: To copy the content of a file to a new file in the same directory

![](./img/18.cp2anotherfile.png)

### `mv` Command: used to rename file

![](./img/19.mvCommand.png)

### `rm` Command: Used to delete files within a directory.

![](./img/20.rmCommand.png)

### `rm -i` Command: prompts system confirmation before deleting a file - (Denotes "interactive").

![](./img/21.rm-i.png)

### `rm -f` Command: allows the system to remove without a confirmation - Denotes "force".

![](./img/22.rm-f.png)

### `rm -r` Command: deletes files and directories recursively.

![](./img/23.rm-r.png)

### `touch` Command: allows you to create an empty file.

![](./img/24.touchCommand.png)

### `find` Command: Used to search for files within a specific directory and perform subsequent operations

![](./img/24.touchCommand.png)

## Conclusion:

### The above implementation demonstrates my application of basic Linux commands. With these skills, I am confident I will advance to proficiency.