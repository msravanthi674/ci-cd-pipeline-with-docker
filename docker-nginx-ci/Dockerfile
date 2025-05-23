# Dockerfile
FROM ubuntu:20.04

RUN apt-get update && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y nginx curl

CMD ["nginx", "-g", "daemon off;"]
