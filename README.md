To start the project through the terminal, enter the SpringBootWeb folder where the pom.xml file is located and type the command:

mvn spring-boot:run

Through the browser enter the address:
  http://localhost:8080/

====================================================

For the application to work in the war format, copy the SpringBootWeb.war file that is inside the /target folder to the Apache Tomcat/webapps folder.

Start the Tomcat service from the terminal by typing the command:
  ./catalina.sh start

Access the Apache Tomcat server through the address:
  http://localhost:8080/SpringBootWeb/counter
