# shell command list

### pwd
shows the current path in a hierarchical directory

---
### cd
change directory

---
### ls
list files and directories

---
### tip
Autocompletion: If you press the *"tab"* key, it will be completed automatically

past command: The previous command is automatically completed when you press the *'up arrow'* key

---
### clear
clear command window

---
# manipulation list

### cp
copy files and directories

#### cp file1 file2
Copies the contrnts of file1 into file2.
If file2 does not exist, it is creat;
Otherwise, file2 is silently overwritten with the contents of file1.
#### cp -i file1 file2
Like above however, since the "-i"(interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
#### cp file1 dir1
Copy the contents of file1(into a file named file1) inside of directory dir1.
#### cp -R dir1 dir2
Copy the contents of the directory dir1. If directory dir2 does not exist, it is created.
Otherwise, it creates a directory named dir1 within directory dir2.

---
### mv
move files and directories or rename them

#### mv file1 file2
If file2 does not exist, then file1 is renamed file2. If file2 exists, its contents are silentl replaced with the contents of file1.
#### mv -i file1 file2
Like above however, since the "-i"(interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
#### mv file1 file2 dir1
The files file1 and file2 are moved to directory dir1. If dir1 does not exist, mv will exit with an error.
#### mv dir1 dir2
If dir2 does not exist, then dir1 is renamed dir2. If file2 exists, the directory dir1 is moved within directory dir2.

---
### rm
delete files and directories permantely and irreversevely

#### rm file1 file2
Delete file1 and file2.
#### rm -i file1 file2
Like above however, since the "-i"(interactive) option is specified, the user is prompted before each file is deleted.
#### rm -r dir1 dir2
Directories dir1 and dir2 are deleted along with all of their contents.

---
### mkdir
make a new directory

---
### wildcards pattern

#### *
All filenames

#### g*
All filenames that brgin with the character "g"

#### b*.txt
All filenames that brgin with the character "b" and end with the characters ".txt"

#### Data???
Any filenames that brgin with the character "Data" followed by exactly 3 more characters

---
### help command

#### help
print command list

#### man
print manual

---
### exit
exit program
