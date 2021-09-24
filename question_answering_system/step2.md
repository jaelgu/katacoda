### 2. Download data and Run web-server docker

#### Download data
Download example data with insurance related questions & answers. Download to your local machine and it will be used later.

`wget https://raw.githubusercontent.com/milvus-io/bootcamp/master/solutions/question_answering_system/data/example.csv`

#### Run qa-chatbot-server docker
Run server with Docker & your host address.

`docker run -d -p 8000:8000 -e "MILVUS_HOST=host_address" -e "MILVUS_PORT=19530" -e "MYSQL_HOST=host_address" milvusbootcamp/qa-chatbot-server:v1`

For example, my host address is 172.17.0.37:

`docker run -d -p 8000:8000 -e "MILVUS_HOST=172.17.0.37" -e "MILVUS_PORT=19530" -e "MYSQL_HOST=172.17.0.37" milvusbootcamp/qa-chatbot-server:v1`{{execute}}
