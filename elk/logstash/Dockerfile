FROM docker.elastic.co/logstash/logstash:6.2.4

COPY logstash.conf /config-dir/

CMD ["-f", "/config-dir/logstash.conf"]