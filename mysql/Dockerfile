FROM mysql:5.7

RUN mkdir sql
WORKDIR /sql

COPY test.sql /sql/test.sql

# Environment variables
ENV MYSQL_USER catalin
ENV MYSQL_PASSWORD catalin
ENV MYSQL_DATABASE day7

RUN mysql -u root -p < /sql/test.sql
