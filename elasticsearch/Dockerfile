FROM elasticsearch:6.6.0

LABEL maintainer="Derek Belrose <dbelrose@jhu.edu>"

RUN bin/elasticsearch-plugin remove ingest-geoip && \
    bin/elasticsearch-plugin install -b ingest-geoip