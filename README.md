# json-server
Demo of the JSON server for fake JSON data

We can use this url: http://jsonplaceholder.typicode.com/

OR... make this server to do locally.

Following tutorial video: https://www.youtube.com/watch?v=1zkgdLZEdwM

### Basic install start

* `npm init` (use a nam other than json-server or it won;t work)
* `D:\WEBDEV\demos\json-server>npm install --save json-server`

### Basic install start

* Now we need to make a script to start the json server
* We can start the server with: `json-server --watch db.json`
* Let's make this an npm scripts
* In scripts in package.json in json:server
* `"json:server":"json-server --watch db.json"`

* Next we have to create our data file - call it db.json
* This is going to be a basic json file
* Get the starter data from http://jsonplaceholder.typicode.com/users
* Add fake data

* Start server:  `npm run json:server`

* Should get a result like:
```

 Loading db.json
 Done

 Resources
 http://localhost:3000/users
 http://localhost:3000/companies

 Home
 http://localhost:3000

 Type s + enter at any time to create a snapshot of the database
 Watching...

```
