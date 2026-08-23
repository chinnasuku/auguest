\#!/bin/bash

set -e

sudo apt update -y

sudo apt upgrade -y

sudo apt install -y openjdk-21-jdk

java -version

curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2026.key | sudo tee \\

&#x20; /usr/share/keyrings/jenkins-keyring.asc > /dev/null



echo deb \[signed-by=/usr/share/keyrings/jenkins-keyring.asc] \\

&#x20; https://pkg.jenkins.io/debian-stable binary/ | sudo tee \\

&#x20; /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt update -y

sudo apt install -y jenkins

sudo systemctl start jenkins

sudo systemctl enable jenkins

sudo systemctl status Jenkins



ghp\_XcBkfD4qqOKB0a5bMqqjOcW1kKPWJ30NXpMh



http://localhost:8080



ngrok http 8080



install Jenkins on amazon Linux



yum install java-21-amazon-corretto -y

wget https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.120/bin/apache-tomcat-9.0.120.tar.gz

tar -zxvf apache-tomcat-9.0.120.tar.gz

sed -i '56  a\\<role rolename="manager-gui"/>' apache-tomcat-9.0.120/conf/tomcat-users.xml

sed -i '57  a\\<role rolename="manager-script"/>' apache-tomcat-9.0.120/conf/tomcat-users.xml

sed -i '58  a\\<user username="surekha" password="Chinnasuku@1718" roles="manager-gui, manager-script"/>' apache-tomcat-9.0.120/conf/tomcat-users.xml

sed -i '59  a\\</tomcat-users>' apache-tomcat-9.0.120/conf/tomcat-users.xml

sed -i '56d' apache-tomcat-9.0.120/conf/tomcat-users.xml

sed -i '21d' apache-tomcat-9.0.120/webapps/manager/META-INF/context.xml

sed -i '22d'  apache-tomcat-9.0.120/webapps/manager/META-INF/context.xml

sh apache-tomcat-9.0.120/bin/startup.sh



https://dlcdn.apache.org/



clean package



**Bulit-In Node off line:**

sudo mkdir -p /var/tmp\_disk

sudo chmod 1777 /var/tmp\_disk

sudo mount --bind /var/tmp\_disk /tmp

echo \*/var/tmp\_disk /tmp none bind 0 0\*|sudo tee-a /etc/fstab

sudo systemctl mask tmp.mount

&#x20;df -h /tmp

sudo systemctl restart jenkins

