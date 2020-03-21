web: java $JAVA_OPTS -Dserver.port=$PORT -jar target/tracker-server.jar debug.xml
heroku ps:scale web=1
#web: java -jar target/tracker-server.jar
#web java -Dserver.port=$PORT -Dspring.profiles.active=heroku $JAVA_OPTS -jar target/tracker-server.jar

