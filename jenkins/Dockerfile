FROM jenkins/jenkins:lts

#COPY https.pem /var/lib/jenkins/cert
#COPY https.key /var/lib/jenkins/pk
#ENV JENKINS_OPTS --httpPort=-1 --httpsPort=8083 --httpsCertificate=/var/lib/jenkins/cert --httpsPrivateKey=/var/lib/jenkins/pk
ENV JENKINS_HOME=/var/jenkins_home
ENV JENKINS_OPTS --httpPort=8080
EXPOSE 8080
