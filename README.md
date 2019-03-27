docker build -t docker-elasticsearch .

docker run -d -p 9200:9200 docker-elasticsearch

http://10.145.89.1:9200/

{
  "name" : "Qtmn2TU",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "esBujA2fQ0WlxPGO2bZD9A",
  "version" : {
    "number" : "6.6.1",
    "build_flavor" : "oss",
    "build_type" : "tar",
    "build_hash" : "1fd8f69",
    "build_date" : "2019-02-13T17:10:04.160291Z",
    "build_snapshot" : false,
    "lucene_version" : "7.6.0",
    "minimum_wire_compatibility_version" : "5.6.0",
    "minimum_index_compatibility_version" : "5.0.0"
  },
  "tagline" : "You Know, for Search"
}

docker-elasticsearch   latest              1fc33f21bfae        2 minutes ago       123MB
