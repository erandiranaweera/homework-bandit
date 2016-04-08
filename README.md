# homework-bandit

Bandit war game in war gaming site called overthewire.org is good for beginners who wants to learn basic Linux commands. Game is organized in levels we have to start from level 0 and with given Linux command hints one can unlock and proceed to the next levels. Game contains 27 levels.

Level 0

In order to proceed with level 0 here  we ssh to bandit0@bandit.labs.org using  bandit0 password.

![image](https://cloud.githubusercontent.com/assets/18344284/14377947/23916066-fd90-11e5-9d56-e2316b7594ad.png)

Level 0 -> Level 1 

The password for the next level is stored in a file called readme located in the home directory.Using ‘cat’ command password is grabbed for level 1.

Cat - read data from files 

![image](https://cloud.githubusercontent.com/assets/18344284/14377963/3d21d402-fd90-11e5-9b59-beff1409f623.png)

Level 1 -> Level 2

The password is in a file called - located in the home directory. Here ls and cat command used for grab password.

ls –  list directory content of files and directories

![image](https://cloud.githubusercontent.com/assets/18344284/14377967/439b27ca-fd90-11e5-9ec6-517a2c61fa99.png)

Level 2 -> Level 3

The password for the next level is stored in a file called 'spaces in this filename'.
Used commands are ls and cat.

![image](https://cloud.githubusercontent.com/assets/18344284/14377971/4b80a60e-fd90-11e5-812a-8960f55eb2c6.png)

Level 3 -> Level 4

Used commands - ls,cd,cat 
Here password is stored in a hidden file in the inhere directory.
ls-la -list command - long format including hidden files

![image](https://cloud.githubusercontent.com/assets/18344284/14377978/54a83922-fd90-11e5-9b70-b79adac7db0c.png)

Level 4 -> Level 5

Used commands for this level  are ls,cd,cat and file.

![image](https://cloud.githubusercontent.com/assets/18344284/14377992/61411514-fd90-11e5-83b1-8bc1a4c5a4df.png)

Level 5 -> Level 6  

File which stored password contain following properties : - human-readable - 1033 bytes in size - not executable

![image](https://cloud.githubusercontent.com/assets/18344284/14378000/6c309be8-fd90-11e5-8592-b096b5fb66a6.png)

Level 6 -> Level 7

Used commands are cat and find.
find command- for search files

![image](https://cloud.githubusercontent.com/assets/18344284/14378006/760ac86e-fd90-11e5-8490-af64359038ce.png)

Level 7 -> Level 8

Here password for the next level is stored in the file data.txt next to the word millionth. Therefore 'grep' command is used here.
grep command - used to search text in given file or line conataining a match to the given string or words.

![image](https://cloud.githubusercontent.com/assets/18344284/14378014/7da71dfc-fd90-11e5-8446-ba8a39d3bbfb.png)

Level 8 -> Level 9

Used commands are ls,cat,sort,uniq.
uniq command - used for filters out repeated lines in a file
sort command - used for sorts the contents of a text file, line by line

![image](https://cloud.githubusercontent.com/assets/18344284/14378021/88f7f474-fd90-11e5-84cd-a360388629fd.png)

Level 9 -> Level 10

Here string command is used to grab password.
String command - print the strings of printable characters in files.

![image](https://cloud.githubusercontent.com/assets/18344284/14378031/92d803c6-fd90-11e5-831d-2b93029a498d.png)

Level 10 -> Level 11

In this level  file data.txt  contains base64 encoded data therefore base64 command is used here.
base64 - base64 encode/decode data and print to standard output

![image](https://cloud.githubusercontent.com/assets/18344284/14378037/9963c888-fd90-11e5-9d5a-a18b3eddf9de.png)

Level 11 -> Level 12

Used commands - ls,cat,tr
tr command - for translate or delete characters

![image](https://cloud.githubusercontent.com/assets/18344284/14378054/bb6a6cd4-fd90-11e5-83ac-ab9bb8d8b899.png)

Level 12 -> Level 13



![image](https://cloud.githubusercontent.com/assets/18344284/14378062/c39ec7d8-fd90-11e5-83ca-124eabd8a846.png)

