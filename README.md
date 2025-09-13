# Ex-1:Linux Commands
## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 lls
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
p<img width="745" height="141" alt="image" src="https://github.com/user-attachments/assets/1b5efee7-e386-485f-aea6-1f49003ff033" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="733" height="65" alt="image" src="https://github.com/user-attachments/assets/f953fd28-3531-4fca-bf5f-39cf0ff28107" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="754" height="58" alt="image" src="https://github.com/user-attachments/assets/77f1fa13-1bd1-4640-be65-beec78b932ef" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>
<img width="739" height="50" alt="image" src="https://github.com/user-attachments/assets/6be6a01f-e4cf-4ec8-b249-9177da70ddd7" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
clear'<img width="747" height="64" alt="image" src="https://github.com/user-attachments/assets/c47b07c6-f203-4a2b-9cbe-de9a1e61453a" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

 <img width="735" height="224" alt="image" src="https://github.com/user-attachments/assets/7895bba8-7a41-42f2-8b63-ced92d05b3a7" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
cl<img width="742" height="215" alt="image" src="https://github.com/user-attachments/assets/d4644d56-4977-499a-a11e-cee1fe1fedc5" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>
<img width="741" height="121" alt="image" src="https://github.com/user-attachments/assets/d3a921ea-3362-42ff-bc96-2329b995bf9f" />



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>
<img width="749" height="60" alt="image" src="https://github.com/user-attachments/assets/736c1062-aac0-4ae7-b117-9979b288191d" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="744" height="125" alt="image" src="https://github.com/user-attachments/assets/b01d7c5b-9526-4d62-9c5a-5d1cf52dbcfa" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
<img width="740" height="241" alt="image" src="https://github.com/user-attachments/assets/a82d96ee-8162-435b-bf64-a030c132ef62" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="736" height="223" alt="image" src="https://github.com/user-attachments/assets/d67d1a34-83a4-4441-80de-36ca58e2dba1" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="746" height="109" alt="image" src="https://github.com/user-attachments/assets/bb3dc135-1240-417c-af4c-73421a64a74c" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
<img width="749" height="117" alt="image" src="https://github.com/user-attachments/assets/b44e5da0-1fd7-451c-b55b-1528842298b9" />

### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>
<img width="745" height="185" alt="image" src="https://github.com/user-attachments/assets/e573ebd0-10ca-4f98-b155-437c0e3dcbb3" />

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
<img width="758" height="75" alt="image" src="https://github.com/user-attachments/assets/db623142-68f0-42a1-ab4b-c2c85805ebd9" />

### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name
<img width="683" height="53" alt="image" src="https://github.com/user-attachments/assets/c5808ceb-a70d-43c0-8b22-dd254d5c69b0" />


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
<img width="611" height="51" alt="image" src="https://github.com/user-attachments/assets/ebb6a6b6-70ea-40f9-bdc7-6bf355dd3d9c" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
<img width="735" height="443" alt="image" src="https://github.com/user-attachments/assets/74b70012-90b3-4816-bbc1-5c3e73e50f34" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
<img width="727" height="147" alt="image" src="https://github.com/user-attachments/assets/30eb9620-2ae0-430f-a50a-1d34ad32e9b1" />
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>
<img width="748" height="83" alt="image" src="https://github.com/user-attachments/assets/ffecda0c-f2dc-4a32-b7e5-64a506477ecf" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="744" height="112" alt="image" src="https://github.com/user-attachments/assets/04e1eea7-b830-4740-aceb-4db89da56245" />

### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 <img width="742" height="196" alt="image" src="https://github.com/user-attachments/assets/74d0671c-2922-4fee-870b-2615f01ee028" />

### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="741" height="249" alt="image" src="https://github.com/user-attachments/assets/08faa3d9-52d2-4f3d-b379-a190c7c5b8de" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="743" height="81" alt="image" src="https://github.com/user-attachments/assets/01b662ec-9892-474e-9e32-c3e4140b10e7" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="736" height="139" alt="image" src="https://github.com/user-attachments/assets/4ad1b042-dfcc-4dae-ba11-4afb34ab8273" />

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="737" height="272" alt="image" src="https://github.com/user-attachments/assets/09bd3471-df3c-4abf-9992-9cf698e290d0" />

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="755" height="81" alt="image" src="https://github.com/user-attachments/assets/3a6967f5-bcc2-4602-8856-85874cc39aa0" />




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
