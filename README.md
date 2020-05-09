# mongo_foundations


## CAP Theorem

C - Consistency 
A - Availibility
P - Partition Tolerance

MongoDB priortizes C & P. 


## Types Of NoSQL Databases

1. Relational Database
    - SQL Server
    - Maria DB
    - Oracle DB
2. Document Database
    - MongoDB
    - CouchDB
3. Key-Value Database
    - Redis
    - DynamoDB
4. Wide-Column Stores
    - Cassandra
    - HBase
5. Graph Database
    - Neo4j
    - JanusGraph


## Advantages Of Document Database

- Intuitive Data Model
- Flexible Schema
- Universal JSON Documents
- Query Data Anyway
- Distrubuted Scalable Database

## Why MongoDB
- Open Source and Free ( Community Edition )
- Document Database
- High Performance
- Rich Query Model
- High Availibility
- Horizantal Scalibility
- Multiple Storage Engines

## SQL Terms Vs MongoDB Terms

|SQL|MongoDB|
|--|--|
|Database | Database|
|Table   | Collection|
|Row | JSON/BSON Document|
|Column | Field|
|Index | Index|

## JSON Vs BSON

|-|JSON|BSON|
|--|--|--|
|Encoding|UTF-8|Binary|
|Data Support|String,Boolean, Number, Array|String, Boolean, Number, Array, Date, Raw Binary|
|Readibility|Human & Machine|Machine Only|

## Run A Docker MongoDB

To start a mongo container
```bash
docker run -p 27017:27017 -d --name mongo mongo 
```

To get into the mongo container
```
docker exec -it mongo /bin/bash
```