FROM almalinux:9 
RUN dnf install git -y
RUN useradd roboshop
USER roboshop
CMD [ "nginx", "-g", "daemon off;" ]