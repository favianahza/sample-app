FROM jenkins/jenkins:lts
USER root
RUN apt update -y && apt install python3 python3-pip -y && python3 -m pip install flask pytest
