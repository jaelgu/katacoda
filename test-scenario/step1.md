## a

`python3 --version`{{execute}}

`wget https://github.com/towhee-io/towhee-docs/raw/main/static/img/logo.png`{{execute}}

`pip install -i https://test.pypi.org/simple/ towhee==0.3.1.dev19`{{execute}}



`vim`{{execute}}

```
from towhee import pipeline
p=pipeline('towhee/image-embedding-resnet50')
img = './logo.png'
emb = p(img)
emb
```

`from towhee import pipeline
p=pipeline('towhee/image-embedding-resnet50')
img = './logo.png'
emb = p(img)
emb`{{execute}}
