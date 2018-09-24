# Repo of Graph Connect 2k18 session "Empower Data Projects With Apache Zeppelin and Neo4j"

For your local setup, just change lines 16, 17, 27, 28 and 29 of neo4j-zeppelin.yml in order to provide a correct path.

Spin-up the stack

```
docker-compose -f .\neo4j-zeppelin.yml up
```

Note that the "Load Dependencies" notebook must be executed just once at the first start of Zeppelin