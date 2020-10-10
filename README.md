# GrailsDocker

**Need to install in local machine.**

1. Java 8
2. Grails 4
3. Docker

Download the repository **git clone https://github.com/rashed-08/GrailsDocker.git**

Goto directory
**cd direcotry**

**Run** \
(For First time)\
**Step-1:** ./gradlew prepareDocker\
**Step-2:** docker build -t --tag="demo:v1" build/docker (use sudo for as normal user)\
**Step-3:** docker run -it -p 8080:8080 demo:v1\
\
Furture change **rebuild** and **rerun**\

