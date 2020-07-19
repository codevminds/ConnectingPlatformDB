# ConnectingPlatformDB

This provides the backend support for the application(ConnectingPlatform)

To configure the DB locally - install Mongo DB .

Steps to be follow :
--------------------

1. Download msi for windows
https://www.mongodb.com/try/download/community

can also follow - https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows-unattended/#install-mongodb-community-edition



2.Connect to MongoDB
On Command prompt - "Mongo" to connect to the MongoDB instance

"C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe"

3.Few commands to start with,

"mongodb://localhost:27017"

"C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe"

db

use <database>
  
db.getSiblingDB()

db.getSiblingDB(<database>)
  
mongo --version

mongod

mongo


4. Projection, DDL & DML Commands 
https://docs.mongodb.com/manual/crud/
