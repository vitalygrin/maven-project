FROM tomcat:8.0

ADD ./webapp/target/*.war /usr/local/tomcat/webaps

EXPOSE 8080

CMD ["catalina.sh", "run"]