FROM postgres:9.6.5

RUN apt-get update && apt-get install -y netcat
ADD start-replicating-postgres.sh /docker-new-entrypoint.sh

ENTRYPOINT ["/docker-new-entrypoint.sh"]
