ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

ADD ./AirbnbIstanbul.csv /usr/share/logstash/data/
ADD ./MarketSales.csv /usr/share/logstash/data/

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
