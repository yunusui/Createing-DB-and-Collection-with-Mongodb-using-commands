# Createing-DB-and-Collection-with-Mongodb-using-commands
Createing DB and Collection with Mongodb using commands

MongoDB
-------
> mongod
> mongo
> use testdb;
> db.createCollection("nodejs");
> db.nodejs.insert({sno:1,topic:"Http Server"});
        ----
        ----
        ----
> db.nodejs.find().pretty();        

********************************************
host      :  localhost
protocol  :  mongodb
port      :  27017
database  :  testdb
collection:  nodejs
********************************************

download the node modules using npm

    => express
    => mongodb@2.2.32
    => body-parser
    => cors
    nodemon for nodemon server (optional)
