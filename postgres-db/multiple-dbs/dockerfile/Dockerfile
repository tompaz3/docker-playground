FROM postgres:14.2-alpine
COPY ./create-db.sh /docker-entrypoint-initdb.d/
RUN chmod 755 /docker-entrypoint-initdb.d/create-db.sh
