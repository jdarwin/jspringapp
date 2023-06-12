FROM mysql:5.7.25
LABEL "Project"="javaspring-app"
LABEL "Author"="Johnny"

ENV MYSQL_ROOT_PASSWORD="javaspringdbpass"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
