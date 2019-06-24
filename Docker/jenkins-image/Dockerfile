FROM jenkins/jenkins:2.164.3
COPY plugins.txt plugins.txt
COPY install-plugins.sh install-plugins.sh
RUN install-plugins.sh < plugins.txt

#ENV JAVA_OPTS= "-Xmx2048m -XX:MaxPermSize=512m  -DsessionTimeout=10080 -Dhudson.model.DirectoryBrowserSupport.CSP=\"img-src 'self'; style-src 'self' 'unsafe-inline';\" -Djenkins.install.runSetupWizard=false"
