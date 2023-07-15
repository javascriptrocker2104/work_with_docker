FROM postgres:latest
ENV POSTGRES_PASSWORD=js_and_py
ENV POSTGRES_USER=anne
ENV POSTGRES_DB=database
COPY init_scripts/init.sql /docker-entrypoint-initdb.d/init.sql
