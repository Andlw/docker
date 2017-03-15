#Dockerfile
#centos7
FROM  centos:7
MAINTAINER  liuwei
RUN yum install -y gcc  gcc-c++ \
    &&  cp  /usr/share/zoneinfo/Asia/Shanghai /etc/localtime  \
    &&  wget -O /usr/local/bin/gosu "https://github.com/tianon/gosu/releases/download/1.7/gosu-x86_64"  \
    &&  chmod +x  /usr/local/bin/gosu \
    &&  gosu  nobody  true
