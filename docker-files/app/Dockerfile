FROM tomcat:8-jre11
LABEL "Project"="javaspring-app"
LABEL "Author"="Johnny"

RUN rm -rf /usr/local/tomcat/webapps/*
COPY javaspring-app.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD ["catalina.sh", "run"]
WORKDIR /usr/local/tomcat/
VOLUME /usr/local/tomcat/webapps
