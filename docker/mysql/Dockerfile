FROM mysql:8.0

ENV MYSQL_DATABASE=django_local
ENV MYSQL_USER=django_user
ENV MYSQL_PASSWORD=secret
ENV MYSQL_ROOT_PASSWORD=secret
ENV TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf
