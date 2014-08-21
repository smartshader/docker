# Version: 0.0.1

FROM ubuntu:14.04
MAINTAINER IMAD JERRA "smartshader@gmail.com"
RUN apt-get update -qq
RUN apt-get install -y nginx
RUN echo "Done!" > /usr/share/nginx/html/index.html
ENTRYPOINT ["/usr/sbin/nginx"] 
CMD ["-h"]
EXPOSE 80
