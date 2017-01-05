FROM csphere/php-fpm:5.4
MAINTAINER Ebbe < ***mail.com>
ADD init.sh /init.sh
ENTRYPOINT ["/init.sh", "/usr/bin/supervisord", "-n", "-c", "/etc/supervisord.conf"]
