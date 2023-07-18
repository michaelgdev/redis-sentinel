==REDIS==
redis-cli -h localhost -p 6379 -a 1234
redis-cli -h localhost -p 6380 -a 1234
redis-cli -h localhost -p 6381 -a 1234
INFO REPLICATION

==SENTINEL==
redis-cli -h localhost -p 26379
INFO SENTINEL

==TEST==
SET key12 valuekey12
GET key12