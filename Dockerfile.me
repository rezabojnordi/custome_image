FROM alpine:latest
LABEL maintainer="Vivek Gite webmater@cyberciti.biz"
RUN apk add --update --no-cache openssh  python3 py3-pip openssl ca-certificates sshpass openssh-client rsync git && \
    apk --no-cache add --virtual build-dependencies python3-dev libffi-dev musl-dev gcc cargo openssl-dev libressl-dev build-base && \
    echo 'PasswordAuthentication yes' >> /etc/ssh/sshd_configi && \
    adduser -h /home/reza -s /bin/sh -D reza && \
    pip3 install --upgrade pip wheel && \
    pip3 install --upgrade cryptography cffi && \
    pip3 install ansible-core ansible && \
    pip3 install mitogen ansible-lint jmespath && \
    pip3 install --upgrade pywinrm && \
    apk del build-dependencies && \
    echo -n 'reza:reza@123' | chpasswd
COPY ./entrypoint.sh /entrypoint.sh
RUN chmod +x entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
EXPOSE 22
COPY entrypoint.sh /
