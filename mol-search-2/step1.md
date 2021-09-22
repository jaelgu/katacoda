#### 1. Start Milvus

This demo uses Milvus 2.0.0-RC6 Standalone version. You can refer to [milvus.io](https://milvus.io/docs/v2.0.0/install_standalone-docker.md) to learn about how to install Milvus 2.0. The following steps show how to install Milvus Standalone with docker-compose.

Firstly, download and save docker-compose.standalone.yml as docker-compose.yml:

`wget https://github.com/milvus-io/milvus/releases/download/v2.0.0-rc6/milvus-standalone-docker-compose.yml -O docker-compose.yml`{{execute}}

Then go to the folder containing docker-compose.yml & start Milvus standalone:
`docker-compose up -d`{{execute}}

Check Milvus status:
`docker-compose logs`{{execute}}
