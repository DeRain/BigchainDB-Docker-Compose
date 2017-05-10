### Docker Composer for BigchainDB

Using RethinkDB as backend database. Created according to official guide [https://docs.bigchaindb.com/projects/server/en/latest/appendices/run-with-docker.html](https://docs.bigchaindb.com/projects/server/en/latest/appendices/run-with-docker.html)  

1. Generate public/private keypair and default BigchainDB settings. Run: `docker-compose run bigchaindb configure rethinkdb`. Choose rethinkdb as database host.  
2. Start docker-compose services. Run: `docker-compose up -d`  
