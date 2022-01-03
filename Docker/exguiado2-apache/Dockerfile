FROM redhat/ubi8
MAINTAINER Victoria  vivimarques10@hotmail.com
LABEL description="A custom Apache container based on UBI 8"
RUN yum install -y httpd && \
    yum clean all
RUN echo "Hello from Dockerfile" > /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
