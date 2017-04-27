# Monit configs for Vesta CP on Centos 6
Services for monitoring:
* crond
* dovecot
* exim
* httpd
* mysql
* named
* nginx
* sshd
* vesta-nginx
* vesta-php
* vsftpd

Installation:

    cd /etc/monit.d/
    git clone https://github.com/turkhero/vesta-centos6-monit.git ./ && rm -f README.md
    monit reload


Check service status:

    monit status
