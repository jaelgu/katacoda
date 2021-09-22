### 3. Run mols-search-webclient docker

Click `+` to the right of the `Terminal`, then Select port to view on Host 1 with port 5000, then copy the link for API_URL parameter, for example: https://2886795291-5000-simba10.environments.katacoda.com.

`docker run -d -p 8001:80 -e API_URL=your_url milvusbootcamp/mols-search-webclient:1.0`


For example:

`docker run -d -p 8001:80 -e API_URL=https://2886795291-5000-simba10.environments.katacoda.com milvusbootcamp/mols-search-webclient:1.0`{{execute}}
