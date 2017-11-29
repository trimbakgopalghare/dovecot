# dovecot  
Dependancy resove on centos 7  
yum install gcc   
yum install g++  
yum -y install git make cmake '@Development Tools' boost-devel  
sudo yum -y install glibc-static libstdc++-static  
sudo yum -y install glibc  
sudo yum -y install glibc-*  
yum install openssl-devel  
# dovecot configuration with mysql driver  
 download source code of dovecot from official site.  
 go  to source folder and run bellow command:    
./configure --with-mysql  


