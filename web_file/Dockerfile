FROM tomcat:7.0-alpine


WORKDIR /usr/local/tomcat/

RUN mkdir -p /usr/local/tomcat/ROOT
RUN touch /usr/local/tomcat/ROOT/Config.properties
RUN echo 'app42.paas.db.username = user' > /usr/local/tomcat/ROOT/Config.properties
RUN echo 'app42.paas.db.port = 3306' >> /usr/local/tomcat/ROOT/Config.properties
RUN echo 'app42.paas.db.password = pass' >> /usr/local/tomcat/ROOT/Config.properties
RUN echo 'app42.paas.db.ip = db' >> /usr/local/tomcat/ROOT/Config.properties
RUN echo 'app42.paas.db.name = database' >> /usr/local/tomcat/ROOT/Config.properties

EXPOSE 8080
