FROM tomcat:8.0
RUN locate **/*.war
ADD **/*.war /opt/tomcat/apache-tomcat-8.5.68/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
