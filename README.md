docker build -t docker-elasticsearch .

docker run -d -p 9200:9200 docker-elasticsearch