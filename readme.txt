npm init -y
npm install express

C:\Program Files\MongoDB\Server\4.2\bin

mongod.exe
mongo.exe

how to create database
-->use userdetails
-->show dbs;
-->db
-->db.createCollection('users')
-->show collections
-->insert()
-->insertOne()
-->insertMany()

db.users.insert([
    {"name" : "Ankita" ,
    "Age" : 24 ,
    "Place": "Pune"
    },
    {"name" : "Aishwarya" ,
    "Age" : 24 ,
    "Place": "Narayangaon"
    },
    {"name" : "Prajakta" ,
    "Age" : 25 ,
    "Place": "Australia"
    },
    {"name" : "Vaishali" ,
    "Age" : 23 ,
    "Place": "Mumbai"
    }
    ]);

db.users.find()
db.users.find().pretty()

 db.users.find({"place":"Pune"})

 db.users.remove({"Place":"Pune"})

 db.users.update({"Place":"Mumbai"},{$set:{"name":"Sushil", "Age":25}})
//npm i mongoose

$ npm install mysql