FROM almalinux:9
RUN dnf install nginx-y
#root access is required to create a user or install the packages. Once it is done we need to cone out from the root user.

RUN useradd roboshop

USER roboshop
CMD ["sleep","200"]