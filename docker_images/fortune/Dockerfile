FROM ubuntu:latest
RUN apt-get update; apt-get -y install fortune
ADD fortuneloop.sh /bin/fortuneloop.sh
# ENTRYPOINT /bin/fortuneloop.sh  # exec form, no shell process

# shell form, needs shell
ENTRYPOINT ["/bin/fortuneloop.sh"]
# command args
CMD ["10"]
