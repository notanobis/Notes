#ASAT 
# [[Linux]] Servers
Generate public key:
>shh-keygen -t rsa -b 4092

View key:
>cat ~/ssh/id_rsa.pub

### Root
1st time setup:
>ssh root@s194131

to add user (while in root):
>adduser user_name
>cd /home/user_name
>mkdir .ssh
>cd .ssh/
>vim authorized_keys

copy paste public key 

>usermod -aG sudo user_name

*User modify -add to Group superuser*

#### Settings
>vim /etc/ssh/shhd_config
>PermitRootLogin no
>Password Authentication no

Προσοχή να υπάρχει ένας χρήστης
>systemctl restart ssh.service

#### sudo
Installing sudo as root:
>apt install sudo
>logout

### User
change password:
>passwd

>sudo apt update
>sudo apt upgrade

Caution on what is being upgraded (how long is it going to be down?)

### Firewall
>sudo apt install ufw
>!!! sudo ufw allow ssh !!!
>sudo ufw enable
>sudo ufw allow http https

For particular door
> sudo ufw allow 7845



