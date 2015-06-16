# node-rest

[CREATING A SIMPLE RESTFUL WEB APP WITH NODE.JS, EXPRESS, AND MONGODB](http://cwbuecheler.com/web/tutorials/2014/restful-web-app-node-express-mongodb/)

## Instration

create data directory.

```sh

cd /path/to/node-rest/
mkdir data

```

start mongodb with sample data.

```sh

mongod --dbpath /path/to/node-rest/data

```

using mongo client to insert sample data

```sh
mongo

> use nodetest2
> db.userlist.insert({'username' : 'test1','email' : 'test1@test.com','fullname' : 'Bob Smith','age' : 27,'location' : 'San Francisco','gender' : 'Male'})''''''''''''''''''''''})
```

start node server.

```sh
npm start
```

go to your browser.

http://localhost:3000/

