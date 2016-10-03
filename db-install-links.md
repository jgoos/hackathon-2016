Postgresql op CentOS 7:

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-centos-7


MariaDB op CentOS 7:

https://www.linode.com/docs/databases/mariadb/how-to-install-mariadb-on-centos-7

Of onderstaande

yum install httpd php php-mysql mariadb-server mariadb sqlite php-dom php-mbstring php-gd php-pdo wget
Set SELinux to allow OwnCloud to write the data.

setsebool -P httpd_unified 1<br>
Allow apache in firewall.

firewall-cmd --permanent --zone=public --add-service=http
firewall-cmd --permanent --zone=public --add-service=https
firewall-cmd --reload




