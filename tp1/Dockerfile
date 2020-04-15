FROM alpine:latest
COPY startup.sh scripts/startup.sh
RUN chmod -R 755 /scripts
ENTRYPOINT ["/bin/sh", "/scripts/startup.sh"]