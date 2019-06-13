FROM tomcat:latest
RUN apt-get update && apt-get install sudo && sudo apt-get update
RUN apt-get install openssh-server
RUN sudo service ssh restart
EXPOSE 22