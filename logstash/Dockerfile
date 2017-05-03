# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.3.0
RUN logstash-plugin install logstash-input-s3

ADD config/credentials.yml /tmp/credentials.yml
