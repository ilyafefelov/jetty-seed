# jetty-seed
Starter code using Maven, Jetty and Jersey
Builds a fat jar-with-dependencies using maven-shade-plugin
Runs a jetty server on 8080 with a single resource

# build
mvn install

# run
java -jar jetty-app-{{version}}.jar

# test resource
http://localhost:8080/entry-point/test
