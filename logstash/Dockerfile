FROM logstash
COPY ./types.db /config/
RUN /opt/logstash/bin/logstash-plugin install logstash-filter-aggregate


