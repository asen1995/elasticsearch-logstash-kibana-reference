Installation: 
 
 
 
1. Install elasticsearch

Windows : 

download elasticsearch-6.8.13.zip , extract it and start from /bin/elasticsearch.bat


Linux : 

$wget
https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch6.8.13-linux-x86_64.tar.gz

$tar -xzf elasticsearch-6.8.13-linux-x86_64.tar.gz

./bin/elasticsearch.sh




default start url : http://localhost:9200/


{
  "name" : "9Lyz8_h",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "KD9qF7AgSYm3KwjR3TqcSQ",
  "version" : {
    "number" : "6.8.13",
    "build_flavor" : "default",
    "build_type" : "zip",
    "build_hash" : "be13c69",
    "build_date" : "2020-10-16T09:09:46.555371Z",
    "build_snapshot" : false,
    "lucene_version" : "7.7.3",
    "minimum_wire_compatibility_version" : "5.6.0",
    "minimum_index_compatibility_version" : "5.0.0"
  },
  "tagline" : "You Know, for Search"
}



2. Install Kibana

 

download kibana-6.8.13.zip , extract it and start from /bin/kibana.bat


Linux : 

wget https://artifacts.elastic.co/downloads/kibana/kibana-6.8.13-linuxx86_64.tar.gz

tar -xzf kibana-6.8.13-linux-x86_64.tar.gz

./bin/kibana.sh


default start url : http://localhost:5601/