# Install Milvus
After checking environment, you can follow steps below to install Milvus:

## 1. Download
Download and save docker-compose.standalone.yml as `docker-compose.yml`.

`wget https://github.com/milvus-io/milvus/releases/download/v2.0.0-rc5-hotfix1/milvus-standalone-docker-compose.yml -O docker-compose.yml`{{execute}}

## 2. Start
Create containers and start Milvus Standalone. Make sure that you're under the same directory as the yaml file.

`docker-compose up -d`{{execute}}
