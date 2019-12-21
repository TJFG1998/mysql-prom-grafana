FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=sakila
ENV MYSQL_PASSWORD=root

ADD ./sql_dbs/* /docker-entrypoint-initdb.d/
