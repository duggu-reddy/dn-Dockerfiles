FROM debian:buster-slim
COPY ./weather-forecast.sh /tmp
RUN apt-get update
RUN apt-get install -y jq && \
    apt-get install -y curl && \
    chmod -R 777 /tmp/*.sh
