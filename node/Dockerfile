FROM ubuntu:16.04

RUN apt-get update \
    && apt-get install -y python git curl wget \
    && curl -sL https://deb.nodesource.com/setup_9.x | bash - \
    && apt-get install -y nodejs \
    && wget https://bootstrap.pypa.io/get-pip.py \
    && python get-pip.py \
    && pip install awscli --upgrade --user

CMD ["/bin/bash"]