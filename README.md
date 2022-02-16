# centos8-mirrors

#建议先备份 /etc/yum.repos.d/ 内的文件（CentOS-Linux-*.repo）

cd /etc/yum.repos.d/
wget https://raw.githubusercontent.com/jw8013/centos-mirrors/main/CentOS-Linux-BaseOS.repo

# yum clean all && yum makecache