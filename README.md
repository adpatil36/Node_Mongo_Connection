# Node_Mongo_Connection
Basic code to connect node with mogodb

1. Install Mongodb and node in system
2. Go to the respective directory and use following commands to import documents in the collection<br>
a. mongoimport --db "DB_NAME" --collection "COLLECTION_NAME" --jsonArray --file "JSON_FILE_NAME"<br>
```
mongoimport --db moviehub --collection movies --jsonArray --file movie.json
mongo
```
To see databases
```
show dbs
```
To use the database
```
use "DB_NAME"
show collections
```
To see documents from the collection COLLECTION_NAME"<br>
```
db."COLLECTION_NAME".find()   
```
Run the index.js to start the server.<br>
```
node index.js
```

To list the locations<br>
http://localhost:8080/api/list<br>
Total count of battles<br>
http://localhost:8080/api/count<br>
Multiple Query paramters<br>
http://localhost:8080/api/search?king=Robb%20Stark&location=Riverrun&battle_type=siege

#### NOTE: In my case learningmongo is my database name and movie is my  collection
