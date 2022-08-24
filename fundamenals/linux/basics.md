# Basics



## Introduction to Linux

### Navigating the File Systems

* ls
* locate \<filename>
* passwd (change password)
* mkdir
* nano
* cd

### User Privileges

* ls -la
* Chmod \<number>/\<permission> (change mode)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/04cb3576-394d-490d-b5c5-05f139dcc43e/Untitled.png)

r = read w = write x = execute

* adduser \<new user> (add new user)
* cat /etc/sudoers (show privileges)
* grep ‘\<word>’ \<dir>

### Common Network Commands

* ip a (show all ip)
* ifconfig (same but oldschool)
* iwconfig
* ip n
  * n = neighbour
* arp -a
* ip r
  * r = route
* route
* ping \<ip>
* netstat

### **Viewing, Creating, and Editing Files**

* echo “\<your text>” > \<filename>
* echo “\<your text>” >> \<filename> (not overwriting the file>
* touch \<new file name> - Create file
* nano \<filename> (open text editor)
* mousepad \<filename> (open GUI text editor)

### **Installing and Updating Tools**

* sudo apt update && apt upgrade
* pimpmykali

###
