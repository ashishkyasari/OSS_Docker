FROM centos/systemd

LABEL maintainer="admin@example1.com"

RUN yum -y install httpd; yum clean all; systemctl enable httpd.service

EXPOSE 80:3000

CMD ["/usr/sbin/init"]
