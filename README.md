This actually has Hibernate in it which I'm less interested in. Ideally, move the hibernate to a different repo (or at least another branch).

# war_hello_world

mvn clean install -DskipTests=true; rm -rfv $TOMCAT_HOME/webapps/sridhar*; truncate -s0 $TOMCAT_HOME/logs/catalina.out; cp /Users/ssarnobat/src/webservices/cmp/sridhar2/target/sridhar2.war $TOMCAT_HOME/webapps/;