# Docker Elasticsearch 6 Install

### 1. Pulling the image
```
sudo docker pull elasticsearch:6.4.2
```

### 2. Run
```
sudo docker run --name elasticsearch -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" -d elasticsearch:6.4.2
````