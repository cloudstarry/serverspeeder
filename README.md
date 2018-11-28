Do not support Openvz！！

CentOS6:

* rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-firmware-2.6.32-504.3.3.el6.noarch.rpm

* rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-2.6.32-504.3.3.el6.x86_64.rpm --force

CentOS7: 

* rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-3.10.0-229.1.2.el7.x86_64.rpm --force

(rpm -ivh http://soft.91yun.org/ISO/Linux/CentOS/kernel/kernel-3.10.0-229.1.2.el7.x86_64.rpm –force –nodeps)

cat /boot/grub2/grub.cfg | grep menuentry

grub2-set-default "CentOS Linux (3.10.0-229.1.2.el7.x86_64) 7 (Core)"

grub2-editenv list

* reboot

* uname -r

# I：
    wget -N --no-check-certificate https://github.com/91yun/serverspeeder/raw/master/serverspeeder.sh && bash serverspeeder.sh
# U：
    chattr -i /serverspeeder/etc/apx* && /serverspeeder/bin/serverSpeeder.sh uninstall -f


chattr +i /serverspeeder/etc/apx*
Support CentOS，ubuntu and debian
