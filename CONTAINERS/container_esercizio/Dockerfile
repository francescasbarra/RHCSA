FROM httpd:latest

WORKDIR /usr/local/bin

USER root

COPY --chown=root:root ./script.sh /usr/local/bin/script.sh

RUN chmod +x script.sh 

ENTRYPOINT  ["script.sh"]

