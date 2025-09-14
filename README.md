# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
<img width="930" height="181" alt="image" src="https://github.com/user-attachments/assets/786da905-c4cd-4c26-81a3-1a84271f8e77" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="454" height="159" alt="image" src="https://github.com/user-attachments/assets/d30f4fd5-7094-487b-bb3a-7120ceea4751" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="386" height="98" alt="image" src="https://github.com/user-attachments/assets/c8641c23-2441-4ab7-85ec-c41936bbf02c" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="390" height="90" alt="image" src="https://github.com/user-attachments/assets/7ef1d425-86a8-4317-b660-c8ed46037de9" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
<img width="398" height="108" alt="image" src="https://github.com/user-attachments/assets/0fb9ec38-7265-4fe3-8bb7-cc1dcf8f21a2" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="763" height="359" alt="image" src="https://github.com/user-attachments/assets/1f6f193b-4019-4b5d-8112-78735aaf87e5" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
<img width="542" height="97" alt="image" src="https://github.com/user-attachments/assets/e3e3c34e-a41e-4da2-9be0-106084a13306" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
<img width="931" height="310" alt="image" src="https://github.com/user-attachments/assets/80436db6-b3bf-4aae-97b6-f7d8cf7c6c1a" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="911" height="296" alt="image" src="https://github.com/user-attachments/assets/8021cdcc-7be7-41cb-832a-0f6a48dc7dea" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
<img width="928" height="515" alt="image" src="https://github.com/user-attachments/assets/150e5faf-2b94-48c8-b040-e1d53d91db35" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="929" height="413" alt="image" src="https://github.com/user-attachments/assets/675cc3ae-46a4-45e7-a48c-59b75cea8f3f" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="918" height="393" alt="image" src="https://github.com/user-attachments/assets/f696a354-cea2-4683-84b5-d6f1b33a1cff" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="923" height="155" alt="image" src="https://github.com/user-attachments/assets/0e2ebd8b-4026-47f0-925c-95f1de620e4b" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>
<img width="828" height="223" alt="image" src="https://github.com/user-attachments/assets/8bcbac3e-6ac0-4bbe-ba0d-5b734facb054" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="810" height="157" alt="image" src="https://github.com/user-attachments/assets/2a7cbad6-baf9-4030-ae12-8c1f2d8d3ca0" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="792" height="116" alt="image" src="https://github.com/user-attachments/assets/85903934-f3fa-446f-b6c2-1bc4d11892fb" />
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="915" height="270" alt="image" src="https://github.com/user-attachments/assets/e4b246e5-97b6-4014-a954-10d3a59a1f64" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="922" height="781" alt="image" src="https://github.com/user-attachments/assets/c672db97-3651-4fa7-ae62-bfd214db6f76" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="930" height="538" alt="image" src="https://github.com/user-attachments/assets/575bb697-3ba3-4f45-8bed-02f29083276c" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="930" height="109" alt="image" src="https://github.com/user-attachments/assets/04aa4685-f286-455b-9e8e-747206735256" />

 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="929" height="121" alt="image" src="https://github.com/user-attachments/assets/d4f4d3aa-88e0-4ded-a876-552c0a2d1add" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
<img width="1147" height="179" alt="image" src="https://github.com/user-attachments/assets/7b49a080-6913-4c79-a555-3fa6081a7336" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
<img width="658" height="313" alt="image" src="https://github.com/user-attachments/assets/428151c7-f03f-4634-9d7c-b5d26c698b6c" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="878" height="481" alt="image" src="https://github.com/user-attachments/assets/4005c459-ff56-4f3e-9e66-7817e9b071de" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
<img width="768" height="266" alt="image" src="https://github.com/user-attachments/assets/b7109b11-9280-4776-af72-ebf2d3e9e07b" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="694" height="209" alt="image" src="https://github.com/user-attachments/assets/e824f228-0e42-458d-a124-19966d79591b" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="1149" height="331" alt="image" src="https://github.com/user-attachments/assets/851641d7-38d1-4246-b329-10a7d7b3b5d6" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”
<img width="678" height="179" alt="image" src="https://github.com/user-attachments/assets/9369ed66-adae-46fc-85c1-5f18b1b086e1" />





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
