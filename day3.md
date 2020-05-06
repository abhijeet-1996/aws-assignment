# Command for Remote login

## _**General command**_

#####   ssh username@ip-address 
* After this enter and provide password, you can login.

* But this method of username-password pair increases the chances of Brute Force Attack (anyone can pass all possible combinations of password and can hack the system).

* So,Linux uses the combination of private and public key arrived, while windows still use user-passwrd pair for authentication.

* This public key is on AWS instance in our case it is on ec2.

* And Private Key is nothing but the .pem that is generated.

 ## _**Mobaxtream**_ for windows

But, mobaxterm also uses the above shell command in backend, it is just that we cannot see it because we are using direct UI. 2.For Linux
##### ssh -i <.pem>username@ip-address
# Linux Commands
Conventions :

## _**-Represents root**_
~ - Home directory of current user

/ - Root directory

vi - Tool/program used in linux to create file


# Command and Description
* cd<dir_name>-change directory

* cd /- Takes to root

* cd ~ - Takes to root

* pwd - print working diorectory

* ls - lists the directory/file

* mkdir <dir_name> - Make directory

* clear - clears terminal

* exit - Exit from current shell

* vi <file_name> - create a file and enters in insert mode

* esc - exit from current mode

* :w - Write and save file

* :q - Quit,exit file

* :wq - Save and Exit

* :wq! - Write and Quit Forcefully

* cat <file_name> - Display file content

# PATH
## _**Absolute Pathname**_
* Begins with the root directory and follows the tree branch till desired dir/file.
* Always starts with /
* Example: /home/user
## _**Relative Pathname**_
* Begins with current directory and goes till root.
* . ---> represents current working dir and .. ---> represents parent directory of workking directory.
* Example: ../data/demo.txt

# Q. Which one of the above is better?

 * It depends on the situation, in some we have to use absolute pathname while in others we nay need to use relative pathname.

# RDS (Relational Database Service)

* We can create database using differet engine options like _**MySQL, SQL, Server, Oracle, PostgreSql, Aurora**_ etc.
* We can connect to this database from our local machine.
* Security groups can be created differently.
* Can stop the instance whenever not in use thus by saving credits and money.