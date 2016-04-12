Maven
Java 8
Mysql 5
CDI
Primefaces
DeltaSpike JPA 
DeltaSpike basic setup
Servlet Container dependencies
JSF 2.2
JPA

#####JAVA EE JPA setup

You need to change your **persistence.xml** file and put your login, password and url information about the database.
  	
#####JSF setup

If you are in ServletContainer, like Tomcat or Jetty, alter your pom.xml in order to change the scope of **jsf-api** from
**provided** to **compile**.