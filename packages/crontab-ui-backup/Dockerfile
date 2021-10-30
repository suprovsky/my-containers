FROM crontab-ui:latest

RUN apk update && apt upgrade \
    && apk add rsync openssh-client \
    && mkdir -p /root/.ssh \
    && mkdir -p /backup