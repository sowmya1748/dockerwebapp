FROM mysql:5.7.25

ENV MYSQL_ROOT_PASSWORD="flm@1234"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
