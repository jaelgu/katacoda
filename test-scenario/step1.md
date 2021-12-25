## a

`python3 --version`{{execute}}

`wget https://github.com/towhee-io/towhee-docs/raw/main/static/img/logo.png`{{execute}}

`git clone https://github.com/towhee-io/towhee.git`{{execute}}

`cd towhee`{{execute}}

`python3 setup.py install`{{execute}}

`cd ../`{{execute}}

`vim`{{execute}}

`from towhee import pipeline`{{execute}}

`p=pipeline('towhee/image-embedding-resnet50')`{{execute}}

`img = './logo.png'`{{execute}}

`emb = p(img)`{{execute}}

`print(emb)`{{execute}}

`:wq`{{execute}}

`python3 test.py` {{execute}}

