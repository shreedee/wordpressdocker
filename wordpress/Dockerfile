FROM wordpress:5.2.0-apache
MAINTAINER shree dee <dee@labizbille.com>

EXPOSE 80

COPY addonsandrun.sh /usr/local/bin/

#ENTRYPOINT ["docker-entrypoint.sh"]
ENTRYPOINT ["addonsandrun.sh"]
CMD ["apache2-foreground"]