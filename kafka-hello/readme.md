1. update `sudo name /etc/hosts` after localhost to `kafkaserver` 
2. install kafka using 'brew install kafka' -> this is needed to starting producer/consumer in step 4 & 5
3. create a cluster/topic in `kafka manager` GUI
4. Run producer `kafka-console-producer --broker-list localhost:9092 --topic kafka_test_topic`
5. Run Consumer `kafka-console-consumer --bootstrap-server localhost:9092 --topic kafka_test_topic --from-beginning`


