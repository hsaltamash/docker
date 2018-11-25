FROM tomcat:9

WORKDIR /usr/local/tomcat

COPY tomcat-users.xml /usr/local/tomcat/conf/tomcat-users.xml
COPY server.xml /usr/local/tomcat/conf/server.xml
COPY context.xml /usr/local/tomcat/webapps/manager/META-INF/context.xml

EXPOSE 8080 8443