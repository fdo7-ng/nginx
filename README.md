# nginx

## Manual Procedure to upgrade NGINX

$ sudo yum update -y

Installing a Prebuilt CentOS/RHEL Package from the Official NGINX Repository
Set up the yum repository for RHEL or CentOS by creating the file nginx.repo in /etc/yum.repos.d, for example using vi:

$ sudo vi /etc/yum.repos.d/nginx.repo
Add the following lines to nginx.repo:

[nginx]
name=nginx repo
baseurl=https://nginx.org/packages/mainline/<OS>/<OSRELEASE>/$basearch/
gpgcheck=0
enabled=1

$ sudo yum update -y

## Download file from github
