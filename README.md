# GrailsDocker

# Installation:

  - **Java 8**
  - **Grails 4**
  - **Docker**

# How to run
**Step-1:** `git clone https://github.com/rashed-08/GrailsDocker.git` \
**Step-2:** `GrailsDocker` \
**Step-3:** ``./gradlew prepareDocker`` *(For first time)* \
**Step-4:** `docker build -t --tag="demo:v1" build/docker` \
**Step-5:** ``docker run -it -p 8080:8080 demo:v1``\
\
**Furture any change *rebuild* and *rerun* the docker**

