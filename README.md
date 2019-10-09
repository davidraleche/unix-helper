# Unix Command Helper List
	
### Find in Unix file
```
find . -type f -name "*.*" -exec grep -il "YOUR TEXT" {} \;
```

### Count number of files in unix directory
```
find .//. ! -name . -print | grep -c //
```

### Cat
```
cat file.php
```


### tail
```
tail -n 20 xxx.php
tail -f
```

### Memory space
```
df

du -skh .

```

```
 yum list installed
```


Clam Antivirus
yum install clamav
yum-complete-transaction --cleanup-only
 /etc/init.d/iptables restart
 
 tail -f /var/log/httpd/access_log
 vim /etc/fail2ban/jail.conf 
 /etc/init.d/fail2ban start
  vim /etc/fail2ban/jail.conf 
   yum install fail2ban
   
   ps -ef
   
   vim notrace.conf 

```
1009  rm -f error_log-2019*
 1010  df -lh
 1011  yum install iptraf
 1012  iptraf 
 1013  ps -ef
 1014  ps -ef |less
 1015  service httpd stop
 1016  netstat -natu
 1017  netstat -pnatu
 1018  netstat -patu
 1019  netstat -patu |less
 1020  ps -ef
 1021  php -v
 1022  netstat -patu |less
 1023  netstat -patu
 1024  vim /etc/httpd/conf/httpd.conf
 1025  service httpd start
 1026  netstat -patu
 1027  netstat -pvatu
 1028  yum search root
 1029* yum install chkroo
 1030  chkrootkit 
 1031  yum search anti
 1032  iptraf
 1033  ps -ef | grep httpd
 1034  ps -ef
 1035  ps -aux
 1036  yum search htop
 1037  yum install htop
 1038  yum install perf
 1039  perf
 1040  perf stat
 1041  ps -ef
 1042  strace -p 4322
 1043  yum -y  install strace
 1044  strace -p 4322
 1045  yum -y  install strace
 1046  ps -ef
 1047  strace -p 4522
 1048  tail -f /var/log/httpd/error_log 
 1049  vim v
 1050  vim /vol/www/aptnewyork/define_metatags.php
 1051  history

```
