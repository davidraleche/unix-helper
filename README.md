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
### Find a specific word in Unix file
```
find . -type f -name "*.*" -exec grep -il "YOUR TEXT" {} \;
```

### AWS package release 
```
chkconfig --list httpd
 sudo chkconfig httpd on
 
 cat /etc/system-release
   ```                     

### Count number of files in unix directory
```
find .//. ! -name . -print | grep -c //
```

### Cat
```
cat file.php
```

### hacker helper
https://dfarq.homeip.net/find-php-malware-linux/?cn-reloaded=1


### LINUX Command = Better/Faster than SCP -> Rsync
```
rsync -av --progress --inplace --compress toot@toto.com:/path/to/sourceserver /path/to/newserversirectory
```

### Copy as is - rsync with aws key
```
rsync -avz -e "ssh -i /root/xxxxxx.pem" ec2-user@xxxxxx.com:/var/www/ /var/www/copywww/
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

   yum install iptraf
   iptraf 
   ps -ef
   ps -ef |less
   service httpd stop
   netstat -natu
   netstat -pnatu
   netstat -patu
   netstat -patu |less
   ps -ef
```

```
  yum install chkroo
   chkrootkit 
   yum search anti
   iptraf
   ps -ef | grep httpd
   ps -ef
   ps -aux
```

```
  yum install htop
   yum install perf
   perf
   perf stat
   ps -ef
   strace -p 4322
   yum -y  install strace
   strace -p 4322
   yum -y  install strace
   ps -ef
   strace -p 4522
   tail -f /var/log/httpd/error_log 

```


```
netstat -pvat

    netstat -pvat
    ls
    vim functions.php
    netstat -pvat
    tail -f /var/log/httpd/access_log
    tail -f /var/log/httpd/error_log 
    df
    du -skh
    df
    cd /var/log/
    ls
    df 
  du -skh
    du -skh *
    cd httpd/
    du -skh *
    ls -la
    rm error_log 
    df 
    df 
    touch error_log
    /etc/init.d/httpd restart
    tail -f /var/log/httpd/error_log 
    tail -f /var/log/httpd/access_log
    tail -f /var/log/httpd/access_log
    vin /etc/httpd/conf/httpd.conf
    vim /etc/httpd/conf/httpd.conf
    vim /etc/httpd/conf/httpd.conf
    vim /etc/httpd/conf.modules.d/
    vim /etc/httpd/conf.modules.d/00-proxy.conf 
    vim /etc/httpd/conf.modules.d/00-proxy.conf 
    /etc/init.d/httpd stop
    netstat -pvat
    netstat -pvatu
    /etc/init.d/httpd start

```

### fail2ban
```
    yum search ban
    yum install fail2ban
    vim /etc/fail2ban/jail.
    vim /etc/fail2ban/jail.conf 
    /etc/init.d/fail2ban start
    vim /etc/fail2ban/jail.conf 
    lsof |grep fail
    tail -f /var/log/httpd/access_log
    /etc/init.d/iptables restart
    tail -f /var/log/httpd/access_log
    yum install clamav
  yum-complete-transaction --cleanup-only
    clamscan /vol/www/aptnewyork/
    freshclam 
    clamscan /vol/www/aptnewyork/
    clamscan /vol/www/aptnewyork/en
    clamscan -r /vol/www/aptnewyork/en
    clamscan -r /vol/www/aptnewyork/
    history
    clamscan -h
```

### unix command Find word in files
```
     find . -type f -name "*.*" -exec grep -il "parse" {} \;
    vim /vol/www/aptnewyork/includes/parseRSS.php
     find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
    cd /vol/www/
    ls
    cd aptnewyork/
     find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
    cd en
     find . -type f -name "*.*" -exec grep -il "parseRSS.php" {} \;
  ```
  
  ### Check yum installed modules
  ```
    yum list installed
    yum list installed | grep proxy
    yum list installed | grep 'proxy'
    yum list installed
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
