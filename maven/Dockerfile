
FROM maven:3.6.3-jdk-8 as firststep
ADD ./simple-webapp /opt/simple-webapp
WORKDIR "/opt/simple-webapp"
RUN mvn clean install


FROM icr.io/appcafe/websphere-liberty:latest
COPY --from=firststep /opt/simple-webapp/target/simpleapp.war /config/dropins/




