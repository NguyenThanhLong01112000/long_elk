ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

RUN chmod 777 ./entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
