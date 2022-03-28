#ASAT 

BASH = Born again Shell
ps= process status
- cd = change directory
cd . = here
cd .. =previous folder
cd ../..= two folders back
- mkdir = make directory (folder)
- pwd = print working directory
- ls =  list files
-l ~> display as list
-al ~> show hidden files ./
- touch file.md = create a file
- ~ = /home/user
- rm = remove (file)
-r = recursively delete (folder)
-rf = recursively delete by force (when error)
- mv file .. = move file one folder back
to rename : mv file newfile
- cp ../file . = copy file from one folder back here
-r (for folder)


Ctrl+r --> search through previous commands

bin = binary files
	sbin = superuser binaries
	usr  --> same files in bin
	which ls --> usr/bin
dev = devices
	vda = virtual disk (hard drive) = sda
home = da home of da users

root= da home of da root

cat =concatenate -> opens file

etc = etcetera = etsy
	network -> interfaces

### Help
command -h
command --help
man command
apropos key-word

### Generate password
openssl rand -base64 25
(25 digits)

### tmux
sudo apt install tmux
>tmux

keeps terminal alive when connection is lost with:
>tmux ls (δίνει τα ανοιχτα sessions)
>tmux a -t 0 (αριθμός session)

To exit : Ctrl+b+d
To create new terminal:
>Ctrl+b+c

To go to next terminal :
> Ctrl+b+n

### Automation
Ansible