FROM httpd:2.4-alpine
WORKDIR /usr/local/apache2/htdocs/
RUN rm  *.html
COPY ./public-html/ /usr/local/apache2/htdocs/