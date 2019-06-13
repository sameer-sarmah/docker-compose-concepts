FROM tomcat:latest
RUN apt-get update && apt-get install sudo && \
    sudo apt-get update && apt-get install -y vim && \
    apt-get install -y net-tools && apt-get install -y openssh-server
COPY ./sshd_config /etc/ssh/
RUN sudo service ssh restart
EXPOSE 22