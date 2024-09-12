FROM jenkins/jenkins:lts

# 安装 Maven
USER root
RUN apt-get update && apt-get install -y maven
USER jenkins

ENV M2_HOME=/usr/share/maven
ENV PATH=$M2_HOME/bin:$PATH