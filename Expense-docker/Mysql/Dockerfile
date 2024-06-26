FROM mysql:8
RUN adduser expense
ENV MYSQL_ROOT_PASSWORD=ExpenseApp@1 \
    MYSQL_USER=expense \ 
    MYSQL_PASSWORD=ExpenseApp@1 \
    MYSQL_DATABASE=Transactions 
RUN chown -R expense:expense /var/lib/mysql /var/run/mysqld
COPY scripts/*.sql /docker-entrypoint-initdb.d/