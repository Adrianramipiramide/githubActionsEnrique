FROM httpd:2
RUN apt update && apt install git -y
RUN rm -rf /usr/local/apache2/htdocs
WORKDIR /usr/local/apache2/htdocs
RUN git clone https://github.com/lcx147258369/christmas-tree/ .
EXPOSE 80
CMD ["httpd-foreground"]
