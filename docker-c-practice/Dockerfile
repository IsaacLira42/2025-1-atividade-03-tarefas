FROM fedora:latest

RUN dnf -y update && \
    dnf -y install gcc findutils fish glibc-devel make && \
    dnf clean all

RUN mkdir -p /app
WORKDIR /app

CMD ["fish"]
