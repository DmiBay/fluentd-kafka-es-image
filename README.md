# fluentd-kafka-es-image
Docker image of [Fluentd](https://github.com/fluent/fluentd) with preinstalled 
[ElasticSearch](https://github.com/uken/fluent-plugin-elasticsearch) and 
[Kafka](https://github.com/fluent/fluent-plugin-kafka) plugins

## Overview
This image is based on `gcr.io/google-containers/fluentd-elasticsearch` image 
and has the same entrypoint. The only difference is in preinstalled 
[Kafka plugin](https://github.com/fluent/fluent-plugin-kafka).   
