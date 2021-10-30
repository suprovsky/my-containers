FROM alseambusher/crontab-ui:latest

RUN apk update && apk upgrade \
    && apk add rsync openssh-client \
    && mkdir -p /root/.ssh \
    && mkdir -p /backup