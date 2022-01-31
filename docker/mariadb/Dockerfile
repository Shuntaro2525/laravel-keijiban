FROM mariadb:10.6

ENV MYSQL_DATABASE=laravel_keijiban_db \
  MYSQL_USER=admin \
  MYSQL_PASSWORD=password \
  MYSQL_ROOT_PASSWORD=password \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf