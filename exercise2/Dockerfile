FROM ubuntu:16.04

WORKDIR /downloads

RUN apt-get update && apt-get install -y rtmpdump wget ffmpeg python3-dev python3-setuptools \
    python3-pip python3-crypto python3-requests python3-lxml python-pip \
    php-cli php-curl php-xml php-bcmath && \
    pip3 install --user --upgrade yle-dl && \
    pip install --upgrade yle-dl

CMD [“/bin/bash”]
