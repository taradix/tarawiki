FROM mediawiki:1.45.4-fpm-alpine

COPY docker-entrypoint.sh /
ENTRYPOINT ["/docker-entrypoint.sh"]

CMD ["php-fpm"]
