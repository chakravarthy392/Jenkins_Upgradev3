FROM tomcat:8.0
#COPY $WORKSPACE/java-tomcat-sample-docker/target/java-tomcat-maven-example.war /usr/local/tomcat/webapps/
COPY */*/*.war /usr/local/tomcat/webapps/
EXPOSE 8080
CMD ["catalina.sh", "run"]
