FROM wordpress:latest
COPY docker-entrypoint.sh /usr/local/bin/temp.sh
RUN cd /usr/local/bin/; \
  cat docker-entrypoint.sh > sample.sh; \
  cat temp.sh > docker-entrypoint.sh; \
  rm temp.sh