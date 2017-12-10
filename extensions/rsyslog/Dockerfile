FROM centos:7

RUN yum install -y rsyslog

EXPOSE 514/tcp
EXPOSE 514/udp

CMD ["/usr/sbin/rsyslogd", "-n"]
