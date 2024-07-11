FROM mysql:8.0.33
LABEL "Project"="DevProj"
LABEL "Author"="Asif"

ENV MYSQL_ROOT_PASSWORD="DevProdbpass"
ENV MYSQL_DATABASE="accounts"


ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
