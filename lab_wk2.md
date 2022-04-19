# Part 1- Installing VScode

Install Visual Studio or Visual Studio Code from the internet,
<br> by simply google "Visual Studio Code" and select version for your Operation.
![pic1](lab2/installVS.png)
![pic1](lab2/insideVsCode.png)

# Part 2- Remotely Connecting
First, look up your course-specific account for CSE15L here:<br>
https://sdacs.ucsd.edu/~icc/index.php<br>
Then, use super+T to open a terminal and connect to the server by using `ssh [server_account]` command and input the password.<br>
if connected sucessfully, terminal should display something similar:
![ssh](lab2/ssh.png)  

# Part 3- Trying Some Commands
Commands that can be used in local terminal can also be used while connecting to a server.
![command](lab2/command.png)

The only difference is that command would be operate on the server.

# Part 4- Moving Files with scp
`scp` is a useful command for copying files between servers , `scp` is always run from the client side. The format of the command is <br>
`scp [file_name] [server_account]`
![scp](lab2/scp.png)

# Part 5- Setting an SSH Key
whenever a user try to log in to a server, user needs to retype the password, which is annoy and time consuming.<br>
a way to solve this repetitive action is setting up a SSH Key.
by using `ssh-keygen` on client side, the computer generate a pair of keys, public key and private key on local computer.
<br> After that, create a dictory called `.ssh` on the remote account.
and copy the public key from local computer to server using `scp`.
<br>After copying public key, you should be able to log in without inputting password.
![sshkey1](lab2/sshkery1.png)

# Part 6- Optimizing Remote Running
Instead of logging in server accout to do a few command then quitting it, you can use run command on server by simply add command after `ssh` line.
And even doing multiple commands at the same line by using `;` to seperate commands.
![ple](lab2/ple.png)
