

\# Lab 1 - Question 1



This README contains all the commands executed, outputs, explanations, and screenshots for \*\*Question 1\*\*.



---



\## Question 1.1: User Identity Verification



\*\*Commands Executed:\*\*

```bash

whoami

groups

````



\*\*Corresponding Outputs:\*\*



```

whoami

mifta



groups

mifta adm dialout cdrom floppy sudo audio dip video plugdev users netdev

```



\*\*Explanation After Every Command:\*\*



1\. `whoami`: I used this command to find my login username. The output was `mifta`, which is the username for my account.

2\. `groups`: This command displayed all user groups that my account `mifta` belongs to. I observed a list of all group names, including my main user group.



\*\*Screenshots:\*\*



\* !\[User Identity](1.1\_username\_gorup.png)



---



\## Question 1.2: Workspace Validation



\*\*Commands Executed:\*\*



```bash

pwd

ls -l

```



\*\*Corresponding Outputs:\*\*



```

pwd

/mnt/d/My PC/Desktop/lab\_1



ls -l

total 0

-rwxrwxrwx 1 mifta mifta   79 Jan  4 00:33 README.md

drwxrwxrwx 1 mifta mifta 4096 Jan  4 00:52 question\_1

drwxrwxrwx 1 mifta mifta 4096 Jan  4 00:42 question\_2

drwxrwxrwx 1 mifta mifta 4096 Jan  4 00:42 question\_3

drwxrwxrwx 1 mifta mifta 4096 Jan  4 00:42 question\_4

```



\*\*Explanation After Every Command:\*\*



1\. `pwd`: This command shows the current working directory. I observed that it printed the full path of my current folder.

2\. `ls -l`: This command lists all files and directories in long format, showing permissions, owner, size, and modification date. I observed a detailed list of files and folders in the directory.



\*\*Screenshots:\*\*



\* !\[Workspace](1.2\_workstation.png)



---



\## Question 1.3: Environment Confirmation File



\*\*Commands Executed:\*\*



```bash

echo "Linux user environment verified" > user\_info.txt

cat user\_info.txt

```



\*\*Corresponding Outputs:\*\*



```

Linux user environment verified

```



\*\*Explanation After Every Command:\*\*



1\. `echo "Linux user environment verified" > user\_info.txt`: This command creates a file named `user\_info.txt` and writes the line into it. I observed that the file was successfully created in the current directory.

2\. `cat user\_info.txt`: This command displays the content of the file. I observed that it correctly showed: `Linux user environment verified`.



\*\*Screenshots:\*\*



\* !\[User Info](1.3\_userinfo.png)



---



\## Question 1.4: File Integrity Check



\*\*Commands Executed:\*\*



```bash

wc -m user\_info.txt

```



\*\*Corresponding Outputs:\*\*



```

32 user\_info.txt

```



\*\*Explanation After Every Command:\*\*



1\. `wc -m user\_info.txt`: This command counts the number of characters in `user\_info.txt`. I observed that it displayed the total character count, including spaces and punctuation.



\*\*Screenshots:\*\*



\* !\[File Integrity](1.4\_intigrity.png)



---



\## Files Created During the Lab



\* `user\_info.txt`

\* `answer\_qs1.txt` (contains your answers)



```



This README connects all your screenshots, commands, outputs, and explanations in a neat lab report format.  



If you want, I can \*\*also create the actual `README.md` file\*\* in your folder structure with the markdown already ready so you can just push it to GitHub. Do you want me to do that?

```



