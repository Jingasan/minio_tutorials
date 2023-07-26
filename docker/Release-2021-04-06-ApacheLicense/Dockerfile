##### Production environment #####
FROM minio/minio:RELEASE.2021-04-06T23-11-00Z as releaser

# install necessary packages
COPY docker-entrypoint.sh /docker-entrypoint.sh
RUN chmod +x /docker-entrypoint.sh
ENTRYPOINT ["/docker-entrypoint.sh"]