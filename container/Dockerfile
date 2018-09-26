FROM centos:7

COPY startup.sh /

RUN yum -y install epel-release

RUN yum -y install curl python-pip jq && yum -y clean all && pip install yq

ENTRYPOINT /startup.sh
