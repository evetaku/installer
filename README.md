Automatic Script Installer by KangArie
==========

## Usage
### Centos 6 32/64bit (OpenVZ VPS)
```
wget https://raw.github.com/arieonline/autoscript/master/centos6.sh
sh centos6.sh
```

### Centos 6 32/64bit (KVM VPS)
```
wget https://raw.github.com/arieonline/autoscript/master/centos6-kvm.sh
sh centos6-kvm.sh
```

### Debian 6 32/64bit (OpenVZ VPS)
```
wget https://raw.github.com/arieonline/autoscript/master/debian6.sh
sh debian6.sh
```

### Debian 7 32/64bit (OpenVZ VPS)
```
wget https://raw.github.com/arieonline/autoscript/master/debian7.sh
sh debian7.sh
```

### Ubuntu 13.04 32/64bit (KVM VPS)
```
wget https://raw.github.com/arieonline/autoscript/master/ubuntu1304-kvm.sh
sh ubuntu1304-kvm.sh
```


## Descriptions

### What's services included
* OpenSSH port 22, 80, 143
* Dropbear port 109, 110, 443
* OpenVPN port TCP 1194 (client config - http://[ip]/client.tar)
* Squid port 8080 (limit to IP VPS)
* badvpn-udpgw port 7300

### What's features included
* Webmin http(s)://[ip]:10000/
* vnstat http://[ip]/vnstat/
* MRTG http://[ip]/mrtg/
* Timezone : Asia/Jakarta
* Fail2Ban : [on]
* IPv6     : [off]

### What's tools included
* axel
* bmon
* htop
* iftop
* mtr
* nethogs  

### What's scripts included
* screenfetch (https://github.com/KittyKatt/screenFetch)
* ps_mem.py (https://github.com/pixelb/ps_mem/)
* speedtest-cli (https://github.com/sivel/speedtest-cli)
* bench-network.sh
* user-login.sh
* user-limit.sh
* user-expire.sh

## References
* http://blog.jualssh.com/
* http://blog.jualssh.com/2014/01/centos6-automatic-script-installer/
* http://blog.jualssh.com/2014/01/centos6-kvm-sh-automatic-script-installer/
* http://blog.jualssh.com/2014/01/debian6-sh-automatic-script-installer/
* http://blog.jualssh.com/2014/01/debian7-sh-automatic-script-installer/
