# SpringJava_docker

This is sample Java project on Spring framework. Maven builds java inside docker.

Attached Dockerfile, src/, pom.xml

After downloading them, build and run docker:

docker build -t java-app .

docker run -d -p 8080:8080 java-app
