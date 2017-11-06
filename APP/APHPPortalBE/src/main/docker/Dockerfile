FROM tomcat:8.5-alpine
VOLUME /tmp

COPY APHPPortalBE-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/APHPPortalBE-0.0.1-SNAPSHOT.jar
RUN sh -c 'touch /usr/local/tomcat/webapps/APHPPortalBE-0.0.1-SNAPSHOT.jar'
ENTRYPOINT [ "sh", "-c", "java -Djava.security.egd=file:/dev/./urandom -jar /usr/local/tomcat/webapps/APHPPortalBE-0.0.1-SNAPSHOT.jar" ]

