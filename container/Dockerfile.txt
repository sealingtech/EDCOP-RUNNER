FROM centos:7

COPY startup.sh /

RUN yum -y install curl && yum -y c lean all

ENTRYPOINT /startup.sh
