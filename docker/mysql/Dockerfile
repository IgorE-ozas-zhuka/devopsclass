FROM mysql:5.7.25
LABEL "Author"="IEroshkin"
LABEL "Project"="VProfile_DZ2"
ADD docker/mysql/db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
ENV MYSQL_ROOT_PASSWORD=admin123
ENV MYSQL_DATABASE=db01