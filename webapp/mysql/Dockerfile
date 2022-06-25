# M1Macのため
FROM mysql/mysql-server:5.7

COPY ./db /docker-entrypoint-initdb.d/

ENV MYSQL_ALLOW_EMPTY_PASSWORD=yes MYSQL_DATABASE=isuumo MYSQL_USER=isucon MYSQL_PASSWORD=isucon


CMD ["--character-set-server=utf8mb4"]