# Linux-Basic-Command
Firstly we learn about Linux 
What is linux ?
Linux is an open-source operating system kernel initially developed by Linus Torvalds in 1991. It is the core component of various Linux distributions, also known as "distros," which include the Linux kernel along with additional software such as libraries, utilities, and applications to create a complete operating system.

Key characteristics of Linux include:
Open Source: Linux is distributed under the GNU General Public License (GPL), which allows users to view, modify, and distribute the source code freely.
Stability: Linux is known for its stability and reliability, making it popular for servers and other critical systems.
Security: Linux has a robust security model, with features like user permissions, access controls, and built-in security mechanisms.
Flexibility: Linux can be customized extensively to suit various needs, from embedded systems to desktop computers and servers.
Compatibility: Linux supports a wide range of hardware architectures and is compatible with numerous software applications.
Linux has a large and active community of developers and users who contribute to its ongoing development and improvement. It is widely used in various applications, including web servers, supercomputers, smartphones (Android is based on the Linux kernel), IoT devices, and desktop computers.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
COMMANDS OF LINUX ------
1)
ls: List files and directories in the current directory.
Example: ls
2)
cd: Change directory.
Example: cd /home/user/Documents
3)
pwd: Print working directory (displays the current directory).
Example: pwd
4)
mkdir: Create a new directory.
Example: mkdir new_directory
5)
touch: Create a new empty file.
Example: touch new_file.txt
6)
rm: Remove files or directories.
Example: rm file.txt (to remove a file)
Example: rm -r directory (to remove a directory recursively)
7)
cp: Copy files or directories.
Example: cp file.txt /destination_directory
8)
mv: Move or rename files or directories.
Example: mv file.txt new_location (to move)
Example: mv old_file.txt new_file.txt (to rename)
9)
cat: Concatenate and display the content of files.
Example: cat file.txt
10)
grep: Search for specific patterns in files.
Example: grep "pattern" file.txt
11)
chmod: Change file permissions.
Example: chmod 755 file.txt (gives read, write, and execute permissions to owner, and read and execute permissions to group and others)
12)
sudo: Execute commands with superuser/root privileges.
Example: sudo apt-get update
13)
apt-get or yum: Package management commands for installing, updating, and removing software packages.
Example: sudo apt-get install package_name
14)
man: Display the manual pages for commands.
Example: man ls
15)
echo: Display a line of text/string.
Example: echo "Hello, world!"
16)
grep: Search for patterns within files.
Example: grep "pattern" file.txt
17)
head: Display the first part of a file.
Example: head file.txt
18)
tail: Display the last part of a file.
Example: tail file.txt
19)
find: Search for files and directories.
Example: find /path/to/search -name "filename"
20)
tar: Create, manipulate, or extract tar archives.
Example: tar -czvf archive.tar.gz directory_to_compress
21)
zip/unzip: Compress or extract ZIP archives.
Example: zip -r archive.zip directory_to_compress
unzip archive.zip
22)
wget: Download files from the internet.
Example: wget http://example.com/file.zip
23)
curl: Transfer data from or to a server.
Example: curl -O http://example.com/file.zip
24)
df: Display disk space usage.
Example: df -h
25)
du: Display disk usage of files and directories.
Example: du -h
26)
ps: Display information about active processes.
Example: ps aux
27)
kill: Terminate processes by ID or name.
Example: kill PID
28)
top: Display and update sorted information about processes.
Example: top
29)
ping: Send ICMP echo requests to network hosts.
Example: ping google.com
30)
ifconfig/ip: Display or configure network interface parameters.
Example: ifconfig or ip addr show
31)
scp: Securely copy files between hosts over SSH.
Example: scp file.txt user@remote_host:/path/to/destination
32)
ssh: Secure shell, used to connect to a remote server securely.
Example: ssh username@hostname
33)
chown: Change file owner and group.
Example: chown user:group file.txt
34)
ln: Create links between files.
Example: ln -s /path/to/source /path/to/destination
