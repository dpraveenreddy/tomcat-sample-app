# tomcat-sample-app

A basic tutorial on running a web app on Tomcat using Docker



# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/dpraveenreddy/tomcat-sample-app.git
* cd 'tomcat-sample-app'
* $docker build -t mywebapp .
* $docker run -p 8080:8080 mywebapp
* access application - http://localhost:8080 or http://\<public-ip\>:8080

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
