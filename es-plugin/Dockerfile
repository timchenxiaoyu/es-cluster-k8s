FROM estest
RUN /elasticsearch/bin/plugin install mobz/elasticsearch-head && /elasticsearch/bin/plugin install https://github.com/NLPchina/elasticsearch-sql/releases/download/2.4.5.0/elasticsearch-sql-2.4.5.0.zip && mkdir /elasticsearch/plugins/ik
COPY ik /elasticsearch/plugins/ik/ 
