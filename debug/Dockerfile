FROM almalinux:8
RUN dnf install -y telnet net-tools iproute bind-utils iputils traceroute curl wget nmap
RUN useradd roboshop
USER roboshop
CMD ["sleep","10000"]
