# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.3.1

RUN logstash-plugin install logstash-filter-translate

COPY ./config/logstash.yml /usr/share/logstash/config/logstash.yml
