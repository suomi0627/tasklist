FROM mysql:8.0.16
LABEL maintainer "suomi0627"

COPY mysql.cnf /etc/mysql/conf.d/mysql.cnf
RUN set -eux && \
  mkdir /var/lib/mysql-files