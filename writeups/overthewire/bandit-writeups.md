# Bandit Writeups



## Bandit Writeups

**Level 0 -> 1 :**

* SSH to the host
* **ssh bandit0@bandit.labs.overthewire.org -p2220**
* password : **bandit0**
* command ls to check what file in the directory
* cat readme file
* flag : **boJ9jbbUNNfktd78OOpsqOltutMc3MY1**

**Level 1 -> 2 :**

* **ssh bandit1@bandit.labs.overthewire.org -p2220**
* password : **boJ9jbbUNNfktd78OOpsqOltutMc3MY1**
* cat the dashed file to get the flag. (cat ./-)
* flag : **CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9**

**Level 2 - 3 :**

* **ssh bandit2@bandit.labs.overthewire.org -p2220**
* password : **CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9**
* cat the file with spaces. ( cat 'spaces in this filename' )
* flag : **UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK**

**Level 3 - 4 :**

* **ssh bandit3@bandit.labs.overthewire.org -p2220**
* password : **CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9**
* **ls** to look file in the directory.
* Enter directory named **inhere** using **cd**
* **ls** to check for any file. Which there isn't anything.
* use ls -a to look for all the file. Saw **.hidden file**
* use **cat** to see the content of the file. (**cat .hidden**)

**Level 4 - 5 :**

* **ssh bandit3@bandit.labs.overthewire.org -p2220**
