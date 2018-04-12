FROM centos

RUN yum install -y httpd git
RUN git clone https://github.com/demoglot/html-samples-food.git /var/www/html

CMD ["httpd", "-DFOREGROUND"]

EXPOSE 80
