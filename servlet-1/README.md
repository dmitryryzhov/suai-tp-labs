# servlet-1
Install Tomcat
==============
1. download [Apache Tomcat](http://tomcat.apache.org/download-60.cgi)
2. unpack to /home/user/apache-tomcat-6.0.47
3. cd /home/user/apache-tomcat-6.0.47/bin
4. run Tomcat: bash ./catalina.sh start

Create first servlet
====================
1. copy files from this repository to /home/user/apache-tomcat-6.0.47/webapps/
2. cd /home/user/apache-tomcat-6.0.47/webapps/servlet-1
3. comile servlet: javac -cp ../../lib/servlet-api.jar:src/ src/TestingServlet.java -d WEB-INF/classes
4. run browser and check static page: http://localhost:8080/servlet-1/index.html
5. run browser and check dynamic page: http://localhost:8080/servlet-1/servlet/Testing

Read
====
1. src/TestingServlet.java
2. WEB-INF/web.xml
3. index.html
