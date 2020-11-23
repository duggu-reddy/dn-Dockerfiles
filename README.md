# dn-Dockerfiles
All my Dockerfiles


# runShell-Dockerfile
To copy and run a shell script as Container. 

To build docker image : `docker build -t ip_forecast:1.0 .`\
To list Docker images: `docker images`\
To run docker with runtime parameters: `docker run -it <image-id> /tmp/weather-forecast.sh`\
To run docker with runtime parameters: `docker run -it <image-id> /tmp/weather-forecast.sh 1.1.1.1`
