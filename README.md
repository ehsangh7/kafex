# create a simple Message Broker app 
## written in python


### to run a zookeeper and kafka server

docker compose up -d

### to create a test topic
docker compose exec broker kafka-topics --create --bootstrap-server localhost:9092 --topic test

### to call producer
./producer.py getting_started.ini

### to call consumer
./consumer.py getting_started.ini

