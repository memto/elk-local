ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

RUN curl https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh -o /usr/share/logstash/bin/wait-for-it.sh \
&& chmod +x /usr/share/logstash/bin/wait-for-it.sh

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
