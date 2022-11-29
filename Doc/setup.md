# Setup Nginx on Ubuntu
```
lihan@ubuntu2204:~$ sudo apt update
lihan@ubuntu2204:~$ sudo apt install nginx
lihan@ubuntu2204:~$ sudo ufw status
lihan@ubuntu2204:~$ systemctl status nginx

lihan@ubuntu2204:~$ cd /var/www/html/
lihan@ubuntu2204:~$ vi index.nginx-debian.html

```
# Setup MySQL on Ubuntu
```
lihan@ubuntu2204:~$ sudo apt update
lihan@ubuntu2204:~$ sudo apt install mysql-server
lihan@ubuntu2204:~$ sudo systemctl start mysql.service
lihan@ubuntu2204:~$ systemctl status mysql.service

lihan@ubuntu2204:~$ sudo mysql_secure_installation  //to change MySQL security settings, also setup password

lihan@ubuntu2204:~$ mysql -u root -p
```
