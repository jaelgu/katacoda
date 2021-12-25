## a

`python3 --version`{{execute}}

`wget https://github.com/towhee-io/towhee-docs/raw/main/static/img/logo.png`{{execute}}




`python3`{{execute}}

`from towhee import pipeline`{{execute}}
`p=pipeline('towhee/image-embedding-resnet50')`{{execute}}
`img = './logo.png'`{{execute}}
`emb = p(img)`{{execute}}
`emb`{{execute}}
