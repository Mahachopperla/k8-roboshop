FROM almalinux:9
RUN dnf install telnet curl net-tools iputils bind-utils traceroute -y
RUN useradd roboshop
USER roboshop
CMD ["sleep", "1000000"]