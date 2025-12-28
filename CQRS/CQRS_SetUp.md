## Connect to MYSQL

```sql
mysql -u root -p
```
## Create database

```mysql
create database cqrs_db;
```

## Connect to Cassandra

```
cqlsh localhost 9042

```

## Create schema in cassandra
```
CREATE KEYSPACE cqrs_query
WITH replication = {'class':'SimpleStrategy','replication_factor':1};
```
