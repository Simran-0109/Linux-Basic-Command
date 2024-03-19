# Linux-Basic-Command
1.cd --this is used to change the directory.
   simran@simran-virtual-machine:~/Desktop$ cd
   simran@simran-virtual-machine:~$
   =======================================================
2. i) ls -- this is used to list all the directories. 
 simran@simran-virtual-machine:~$ ls
Desktop  Documents  Downloads  Music  Pictures  Public  snap  Templates  Videos
simran@simran-virtual-machine:~$
---------------------------------------------------
ii) ls -l :-  known as a long format that displays detailed information about files and directories.
 --  simran@simran-virtual-machine:~/Desktop$ ls -l
total 12
-rw-rw-r-- 1 simran simran   31 Mar  5 14:40 example.txt
drwxr-xr-x 9 root   root   4096 Dec 30 17:00 reports
drwxrwxr-x 2 simran simran 4096 Mar  5 14:39 Simran
[there first rw represtent the admin file or directories which is read and write  file  or directories.
then second rw represent the public file or directories whis is read and write  file or directories
and last r represent the group file or directories which is reable only file or directories]

------------------------------------------------------------
iii) ls -a :- Represent all files Include hidden files and directories in the listing.
  simran@simran-virtual-machine:~/Desktop$ ls -a
.  ..  example.txt  reports  Simran
simran@simran-virtual-machine:~/Desktop$

