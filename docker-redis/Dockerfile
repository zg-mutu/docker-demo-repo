FROM centos
MAINTAINER mutu
ENV REFRESHED_AT 2018-3-13
RUN yum update –y && yum -y install wget

RUN yum -y install wget
WORKDIR  /etc/yum.repos.d/
RUN wget http://mirrors.aliyun.com/repo/epel-6.repo
RUN yum -y install redis
EXPOSE 6379


