# a naive Jenkins image
FROM jenkins/jenkins:lts-jdk11
USER root
RUN apt-get update && \
    apt-get install -y mercurial && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
USER jenkins
