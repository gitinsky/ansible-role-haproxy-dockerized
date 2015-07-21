FROM gitinsky/baseimage:0.1.8
MAINTAINER Git In Sky <support@gitinsky.com>
EXPOSE 8080

RUN apt-get update && apt-get -y install haproxy
ADD start.sh /start.sh

CMD ["/start.sh"]
