FROM tomcat:8.5-alpine
VOLUME /tmp
COPY Portal-BE-0.0.1-SNAPSHOT.jar /usr/local/tomcat/webapps/Portal-BE.war
RUN sh -c 'touch /usr/local/tomcat/webapps/Portal-BE.jar'
ENTRYPOINT [ "sh", "-c", "java -Djava.security.egd=file:/dev/./urandom -jar /usr/local/tomcat/webapps/Portal-BE.jar" ]