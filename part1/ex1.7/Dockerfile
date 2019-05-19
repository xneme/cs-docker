FROM ubuntu:latest

WORKDIR /curler
COPY script.sh .
RUN chmod +x ./script.sh
RUN apt-get update && apt-get install -y curl

CMD ["./script.sh"]