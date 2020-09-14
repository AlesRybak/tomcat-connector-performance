FROM tomcat

RUN rmdir webapps && mv webapps.dist webapps

COPY server.xml conf/server.xml
COPY localhost-rsa.jks conf/localhost-rsa.jks
