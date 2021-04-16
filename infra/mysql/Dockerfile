FROM mysql:8.0

RUN chmod -R 644 /etc/mysql/conf.d
RUN sed -e 's/^ *user *= *mysql$/user = root/' -i /etc/mysql/my.cnf