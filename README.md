Zookeeper initiation:
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

Kakfka Server Initiation:
.\bin\windows\kafka-server-start.bat .\config\server.properties
rhrgh

Topic Creation:
.\bin\windows\kafka-topics.bat --create --topic my_topic --bootstrap-server localhost:9092 --partitions 1 --replication-factor 1



To view in Web page:
.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic my_topic
