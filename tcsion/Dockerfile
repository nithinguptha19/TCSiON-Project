from ubuntu:latest
from openjdk:17
run mkdir /opt/tomcat
workdir /opt/tomcat
add https://dlcdn.apache.org/tomcat/tomcat-9/v9.0.65/bin/apache-tomcat-9.0.65.tar.gz .
run tar -xvzf apache-tomcat-9.0.65.tar.gz
run mv apache-tomcat-9.0.65/* /opt/tomcat
expose 8080
copy nithin /opt/tomcat/webapps/nithin
cmd ["/opt/tomcat/bin/catalina.sh", "run"]



