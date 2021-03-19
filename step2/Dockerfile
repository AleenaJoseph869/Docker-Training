FROM php:7.2-cli

EXPOSE 9000
RUN mkdir /myproject
COPY index.php /myproject
WORKDIR /myproject
CMD ["php", "-s", "0.0.0.0:9000"]
