FROM centos

RUN yum -y install httpd

ADD myChallenge2.tar.gz /var/www/html

CMD ["-D", "FOREGROUND"]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80


