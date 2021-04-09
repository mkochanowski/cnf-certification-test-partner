FROM registry.access.redhat.com/ubi7/ubi:latest

RUN yum install -y hostname iproute iputils openssh openssh-clients

RUN yum install -y nmap-ncat

CMD ["tail", "-f", "/dev/null"]
