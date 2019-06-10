FROM jenkins/jenkins:2.164.3
COPY plugins.txt /usr/share/jenkins/ref/plugins.txt
RUN /usr/local/bin/install-plugins.sh < /usr/share/jenkins/ref/plugins.txt
USER root
RUN unlink /etc/localtime
RUN ln -s /usr/share/zoneinfo/Asia/Jerusalem /etc/localtime
