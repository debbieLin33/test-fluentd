FROM java:8

VOLUME /tmp
ADD test-docker-0.0.1-SNAPSHOT.jar /opt/app/test-docker.jar

VOLUME /tmp

USER hbyapp

ENTRYPOINT cd /opt/app; exec java -d64 $JAVA_OPTS -jar test-docker.jar
