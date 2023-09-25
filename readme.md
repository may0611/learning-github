
# Lab 4.  linux CLI study note
                                                                                       202237783 이채은 (소프트웨어학과)
***summary:*** This note is my linux CLI study note. Contains a summary of various shell command commands.

#### **1. pwd**
 pwd: shows the current path in a hierarchical directory
 ```sh
 $ pwd
 /Users/maylee
 ```


#### **2. cd, ls**
- cd: change directory
- ls: list files and directories
-l: show detailed information(long format)
-lh: same as above, but size is units 
```sh
$ pwd
/Users/maylee
$ ls
Applications	Downloads	Music		Public		ps.dSYM
Desktop		Library		Pictures	ps
Documents	Movies		Projects	ps.c
$ cd Projects
$ pwd
/Users/maylee/Projects
$ cd..
$ pwd
/Users/maylee
```
there are some more other arguments:
\- /(root)
\- .(current directory)
\- . .(upper-level directory)
\- ~(home of current user)
\-/[directory name]\(absolute path)
\-./[directory name]\(relative path)
\-. ./[directory name]\(relative path)

#### **3. clear**
```sh
$ pwd
/Users/maylee
$ ls
Applications	Downloads	Music		Public		ps.dSYM
Desktop		Library		Pictures	ps
Documents	Movies		Projects	ps.c
$ clear
```

```sh
maylee@mayui-MacBookPro ~ % 
```

---
 *Warning*: These commands may delete or overwrite your files and directories! Make sure to backup your important contents.

---
#### **4. cp**
cp: copy files and directories.

#### **5. mv**
mv: move files and directories or rename them.
rename- Replicate the original file with a new name and clear the original file

#### **6. rm**
rm: delete the files and directories ***permantely and irreversevely!!!***

---
##### Be careful with rm!
Linux does not have an undelete command. Once you delete something with rm, it's gone. You can inflict terrific damage on your system with rm if you are not careful, particularly with wildcards.
Before you use rm with wildcards, try this helpful trick: construct your command using is instead. By doing this, you can see the effect of your wildcards before you delete files. After you have tested your command with Is, recall the command with the up-arrow key and then substitute rm for is in the command.

---

#### **7. help, man**
Use this to view commands or options that you are not familiar with.











