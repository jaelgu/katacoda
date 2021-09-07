# After Installation...

## Check Status
If Milvus standalone boots successfully, three running docker containers appear (two infrastructure services and one Milvus service).

`docker-compose ps`{{execute}}

The states should be `Up` or `Up (healthy)`. If you see `starting` instead, then wait a while and check again later.

## Uninstall Milvus
You can also uninstall Milvus by deleting docker containers:

`docker-compose down`{{execute}}

If you want to clean up data, delete Milvus volumes under the same directory of the yaml file:

`rm -rf volumes`{{execute}}
