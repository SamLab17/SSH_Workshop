# Basic Linux Commands

## An Introduction/Warning

You are about to see a lot of potentially unfamiliar commands below. **Don't worry about memorizing these.**

The only way of getting familiar with these commands is by using them. So if that means you need to look up a Linux cheatsheet everytime or you print out a list of these on your desk, that's perfectly normal.

Many of these commands have strange, unintuitive names which still cause the most experienced Linux users to forget or confuse them.

## Syntax Used

When a command is shown in a code block, it may be followed by _optional_ or _required_ arguments.

Optional arguments will be enclosed with square brackets: `[optional]`.

Required arguments will be enclosed with angle brackets: `<required>`.

**When you actually enter these commands at a prompt, do not include any brackets.**

## File System Commands

`pwd` - Print the **c**urrent **w**orking **d**irectory.

```bash
pwd
```

---

`ls` - List all of the files in the current directory.

```bash
ls [-a Show hidden files] [-l Show as list with details]
```

---

`rm` - Remove (delete) on or more files

```bash
rm <File 1> [File 2] [File 3] ...
```

---

`cd` - Change directory

```bash
cd <Directory name>
```

Use `cd ..` to go up a directory.

---

`cp` - Copy a file

Usage:

```bash
cp <Source file> <Destination>
```

---

`mkdir` - Create a new directory

```bash
mkdir <New directory name>
```

---

`rmdir` - Delete an empty directory

```bash
rmdir <Directory Name>
```

## File Manipulation Commands

`cat` - Output the contents of a file to the screen

```bash
cat <File name>
```

---

`more` - Output one screenful of a file. Press Enter to scroll down. Press q to quit.

```bash
more <File name>
```

---

`nano` - Open the nano text editor. Use Control+X to exit (you may be prompted to save, type y or n).

```bash
nano [File name]
```

---

`vim` - Open the vim text editor. To quit, first press Escape then type `:q!` to quit without saving, or `:wq` to save and quit.

``` bash
vim [File name]
```
