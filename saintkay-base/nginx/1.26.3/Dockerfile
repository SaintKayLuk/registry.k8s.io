FROM docker.io/nginx:1.26.3

ENV DEBIAN_FRONTEND=noninteractive

RUN apt update && \
    apt install -y iputils-ping telnet net-tools dnsutils curl netcat-openbsd && \
    apt clean && \
    rm -rf /var/lib/apt/lists/*
