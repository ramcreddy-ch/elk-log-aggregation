# ELK Log Aggregation

Configuration for centralized logging using the Elastic Stack (Filebeat, Logstash, Elasticsearch, Kibana).

## Pipeline
1. **Filebeat**: Harvests logs from edge nodes.
2. **Logstash**: Parses/GROKs logs.
3. **Elasticsearch**: Indexes data.
