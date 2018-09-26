FROM centos:7

COPY startup.sh /

RUN yum -y install curl && yum -y clean all

ENTRYPOINT /startup.sh
