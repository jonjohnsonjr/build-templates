FROM ubuntu
COPY ./builder/Dockerfile /builder/Dockerfile
COPY ./web/Dockerfile /web/Dockerfile
CMD mkdir -p /workspace/web && mkdir -p /workspace/builder && cp /web/Dockerfile /workspace/web/Dockerfile && cp /builder/Dockerfile /workspace/builder/Dockerfile
