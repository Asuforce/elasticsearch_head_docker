FROM elasticsearch:5.0.0

RUN elasticsearch-plugin install analysis-kuromoji
RUN elasticsearch-plugin install analysis-icu

RUN apt-get update -qq && apt-get install -qq ruby

COPY elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml
