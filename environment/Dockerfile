# hash:sha256:e3d042c7077ea4339bcf71a68bd7427f9ef7a2d755459536ef8908818089ece2
FROM registry.codeocean.myoctank.net/codeocean/miniconda3:4.9.2-cuda11.7.0-cudnn8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN conda install -y \
        jupyterlab \
    && conda clean -ya

RUN pip3 install -U --no-cache-dir \
    matplotlib==3.8.0 \
    pytest==7.4.2 \
    torch==2.1.0
