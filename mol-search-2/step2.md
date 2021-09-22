#### 2. Download data and Run mols-search-webserver docker

Download the smiles data with molecular.

`wget -P /root/data https://raw.githubusercontent.com/milvus-io/bootcamp/master/solutions/molecular_similarity_search/smiles-data/test_1w.smi`{{execute}}

Run server with Docker.

`docker run -d \
-v /root/data:/mols_data \
--network my-net \
--ip 10.0.0.3 \
-p 5000:5000 \
-e "MILVUS_HOST=10.0.0.2" \
-e "MILVUS_PORT=19530" \
-e "MYSQL_HOST=10.0.0.2" \
milvusbootcamp/mols-search-webserver:2.0.0`{{execute}}

Refer to the following table for the parameter description:

| Parameter                     | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ |
| -v /root/data:/mols_data      | -v specifies directory mapping between the host and the docker image.  |
| -p 5000:5000                  | -p specifies pot mapping between the host and the image.     |
