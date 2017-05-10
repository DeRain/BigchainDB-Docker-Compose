### Docker Composer for BigchainDB

Using RethinkDB as backend database.  

1. Generate public/private keypair and default BigchainDB settings. Run: `docker-compose run --interactive --tty bigchaindb configure rethinkdb`. Choose rethinkdb as database host.  
2. Start docker-compose services. Run: `docker-compose up -d`  
