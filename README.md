# elasticsearch_head_docker

elasticsearch-head on docker sample

## requirements

- docker
- docker-compose

## execute

```bash
$ git clone https://github.com/Asuforce/elasticsearch_head_docker.git
$ cd elasticsearch_head_docker
$ docker-compose up -d
```

you can access es container and start es5

```bash
$ docker-compose exec es /bin/bash
$ systemctl start elasticsearch
```
