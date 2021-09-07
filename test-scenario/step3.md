# Check Status
If Milvus standalone boots successfully, three running docker containers appear (two infrastructure services and one Milvus service).

`docker-compose ps`{{execute}}

The states should be `up` or `up (healthy)`. If you see `starting` instead, then wait a while and check again later.
