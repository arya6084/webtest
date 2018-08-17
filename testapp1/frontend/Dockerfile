FROM ubuntu:18.04
MAINTAINER harsha6084@gmail.com
RUN apt-get -y update
RUN apt-get -y install nginx
ADD code /var/www/html
EXPOSE 80
ENV BACKENDLB=test
CMD ["nginx", "-g", "daemon off;"]