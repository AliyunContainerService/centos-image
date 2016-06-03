FROM centos:7
MAINTAINER Li Yi <denverdino@gmail.com>
RUN sed -i.backup 's/^enabled=1/enabled=0/' /etc/yum/pluginconf.d/fastestmirror.conf
COPY Centos-7.repo /etc/yum.repos.d/CentOS-Base.repo

