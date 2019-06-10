FROM jenkins/jenkins:2.164.3
RUN install-plugins.sh < plugins.txt
USER root
RUN unlink /etc/localtime
RUN ln -s /usr/share/zoneinfo/Asia/Jerusalem /etc/localtime
