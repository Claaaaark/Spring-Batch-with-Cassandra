# Spring batch with Cassandra config.

- **Custom ItemReader and ItemWriter.**
- **Work in a Batch to perform migration**
   
# cassandra
CREATE KEYSPACE "integration" WITH replication = {'class': 'SimpleStrategy', 'replication_factor' : '1'};
