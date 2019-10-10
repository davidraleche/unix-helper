# Unix Command Helper List


Block IPV6 malicious connection
```
 vi /etc/sysconfig/ip6tables
 ```
 
> -A INPUT -m state --state NEW -m tcp -p tcp --dport 80 -j ACCEPT

> -A INPUT -m state --state NEW -m tcp -p tcp --dport 443 -j ACCEPT

> -A INPUT -m state --state NEW -m tcp -p tcp --dport 22 -j ACCEPT
                                                                 
 ```
 service ip6tables restart
 iptables restart
 ```
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

### Linux Iptables Setup Firewall For a Web Server
https://www.cyberciti.biz/faq/linux-web-server-firewall-tutorial/

### yum list isntalled packaged
```
 yum list installed
```


### Clam Antivirus
```
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

##  IPTraf │ An IP Network Statistics Utility 
```
yum install iptraf
iptraf 
```

```

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
```

```
 1029 yum install chkroo
 1030  chkrootkit 
 1031  yum search anti
 1032  iptraf
 1033  ps -ef | grep httpd
 1034  ps -ef
 1035  ps -aux
```

```
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


```


```
netstat -pvat

  660  netstat -pvat
  661  ls
  662  vim functions.php
  663  netstat -pvat
  664  tail -f /var/log/httpd/access_log
  665  tail -f /var/log/httpd/error_log 
  666  df
  667  du -skh
  668  df
  669  cd /var/log/
  670  ls
  671  df 
  672  du -skh
  673  du -skh *
  674  cd httpd/
  675  du -skh *
  676  ls -la
  677  rm error_log 
  678  df 
  679  df 
  680  touch error_log
  681  /etc/init.d/httpd restart
  682  tail -f /var/log/httpd/error_log 
  683  tail -f /var/log/httpd/access_log
  684  tail -f /var/log/httpd/access_log
  685  vin /etc/httpd/conf/httpd.conf
  686  vim /etc/httpd/conf/httpd.conf
  687  vim /etc/httpd/conf/httpd.conf
  688  vim /etc/httpd/conf.modules.d/
  689  vim /etc/httpd/conf.modules.d/00-proxy.conf 
  690  vim /etc/httpd/conf.modules.d/00-proxy.conf 
  691  /etc/init.d/httpd stop
  692  netstat -pvat
  693  netstat -pvatu
  694  /etc/init.d/httpd start

```


```
  767  yum search ban
  768  yum install fail2ban
  769  vim /etc/fail2ban/jail.
  770  vim /etc/fail2ban/jail.conf 
  771  /etc/init.d/fail2ban start
  772  vim /etc/fail2ban/jail.conf 
  773  lsof |grep fail
  774  tail -f /var/log/httpd/access_log
  775  /etc/init.d/iptables restart
  776  tail -f /var/log/httpd/access_log
  777  yum install clamav
  778  yum-complete-transaction --cleanup-only
  779  clamscan /vol/www/aptnewyork/
  780  freshclam 
  781  clamscan /vol/www/aptnewyork/
  782  clamscan /vol/www/aptnewyork/en
  783  clamscan -r /vol/www/aptnewyork/en
  784  clamscan -r /vol/www/aptnewyork/
  785  history
  786  clamscan -h
```

### unix command Find word in files
```
  813   find . -type f -name "*.*" -exec grep -il "parse" {} \;
  814  vim /vol/www/aptnewyork/includes/parseRSS.php
  815   find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
  816  cd /vol/www/
  817  ls
  818  cd aptnewyork/
  819   find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
  820  cd en
  821   find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
  ```
  
  ### Check yum installed modules
  ```
  901  yum list installed
  902  yum list installed | grep proxy
  903  yum list installed | grep 'proxy'
  904  yum list installed
```
### khunter (Rootkit Hunter) is a Unix-based tool that scans for rootkits, backdoors and possible local exploits. It does this by comparing SHA-1 hashes of important files with known good ones in online databases, searching for default directories (of rootkits), wrong permissions, hidden files, suspicious strings in kernel modules, and special tests for Linux and FreeBSD. rkhunter is notable due to its inclusion in popular operating systems (Fedora,[1] Debian,[2] etc.)

```
vim /etc/rkhunter.conf cooment following line
```
> #SCRIPTWHITELIST=/usr/bin/GET

```


   yum search rkhunter 
   yum install rkhunter 
   yum install rkhunter.noarch
   yum search rkhunter 
   yum search perl
   

   rkhunter --update
   rkhunter --propupd
   vim /etc/rkhunter.conf
   rkhunter --propupd
   rkhunter
   rkhunter /vol
   rkhunter /vol/
   ls /
   rkhunter 
   rkhunter vol
   rkhunter --check --sk
 ```
 
 
 ### Check users
 ```
   cat /etc/passwd
   tail -f /var/log/httpd/error_log 
   netstat -pnatu
   vim  /etc/sysctl.conf
   sysctl -p
   vi /etc/ssh/sshd_config
   netstat -pnatu
   /etc/init.d/httpd stop
   netstat -pnatu

   /etc/init.d/httpd start

   netstat -pnatu
   netstat -vnatu
   netstat -vnatu
 ```
 
 ```
   top
   netstat -nlp
   netstat -nl
   netstat -np
   netstat -npatu
   strace -p 21865
   vim /var/www/noindex/index.html
   mv  /var/www/noindex /var/www/SUSPICIOUSnoindex
   ls /etc/httpd/htdocs
   ls /etc/httpd
   strace -p 21865 | grep open
   strace -p 21865 -o open
   ls
   grep open 
   grep open open 
   cat open 
   strace -p 21865 -o open
   netstat -npatu
   service httpd restart
 ```
 
 
 ### Associate process and PID
 ```
   netstat -npatu

Trace PID to source look at (open)
  strace -p 22193
```
### display port
```
 vim /vol/www/aptnewyork/fr/./map_francois.php
 lsof
 lsof | grep php
  
 lsof | grep aptnewyork
 lsof | grep php
 lsof | grep vol
```

### List installed Library php modules
```
   php -m
 ```
