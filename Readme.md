## Setting Up Elasticsearch and Kibana in one Docker container

This Dockerfile sets up a simple and lightweight docker image for Elasticsearch and Kibana.

### Usage

docker run -d -p 9200:9200 -p 5601:5601 stevepop/es-kibana

Once complete, you can then connect to Elasticsearch by navigating to `localhost:9200` and its Kibana front-end at `localhost:5601`.

### Tags

Tag     | Elasticsearch | Kibana
------- | ------------- | ------
latest  | 5.6.2         | 5.6.2
kibana4 | 2.4.1         | 4.6.2
kibana3 | 1.7.4         | 3.1.3
