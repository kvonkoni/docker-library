FROM alpine:latest

RUN apk add --no-cache python3 \
    && python3 -m ensurepip \
    && apk add make automake gcc g++ subversion python3-dev \
    && pip3 install --upgrade pip \
    && pip3 install numpy \
    && pip3 install anytree \
    && pip3 install ete3 \
    && pip3 install graphviz

WORKDIR ./pipeline