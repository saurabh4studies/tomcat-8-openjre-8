# Tomcat-8-openjdk-8 Docker image 

There are several vulnerabilities to the default Apache Tomcat Application server docker image.
So we tried to address those vulnerabilities by 
  1. make sure Tomcat version is not being exposed when an error occur.
  2. make sure that default web.xml listing are set to false.
  3. protect the shutdown port.
  4. secure default manager WebApp.
  
Now this docker image will be ready for production and pass security reviews as well.
So we can say that this Docker image is secured according to OWASP.

You can download Docker image from below link
https://hub.docker.com/r/msaurabh08/tomcat-openjdk

Either you can run the following command to pull this image
docker pull msaurabh08/tomcat-openjdk
