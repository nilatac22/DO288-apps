FROM mysql:5.7

RUN mkdir sql
WORKDIR /sql

# Environment variables
ENV MYSQL_USER catalin
ENV MYSQL_PASSWORD catalin
ENV MYSQL_DATABASE day7

COPY test.sql /sql/test.sql

#RUN mysql -u root -p < /sql/test.sql
