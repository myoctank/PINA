# hash:sha256:9fb68f593533414ff1cd3b9c7542ae273db805203a5c1ae9708ef3a9255edaaf
FROM registry.codeocean.com/codeocean/miniconda3:4.12.0-python3.9-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

RUN pip3 install -U --no-cache-dir \
    matplotlib==3.6.3 \
    pytest==7.2.1 \
    torch==1.13.1
