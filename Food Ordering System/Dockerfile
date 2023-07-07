FROM tomcat:9-jdk8-openjdk-slim
RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/online-food-order-0.0.1-SNAPSHOT.war /usr/local/tomcat/webapps/ROOT.war
EXPOSE 8080
CMD ["catalina.sh", "run"]