##### Production environment #####
FROM minio/minio:latest as releaser

# install necessary packages
COPY docker-entrypoint.sh /docker-entrypoint.sh
RUN chmod +x /docker-entrypoint.sh
ENTRYPOINT ["/docker-entrypoint.sh"]