# Simple Node Server

Simple node + express server with user authentication for articles creating/editing/deleting.

This was made following the Tutorial by Brad Traversy (@bradtraversy), found [here](https://www.youtube.com/watch?v=k_0ZzvHbNBQ&list=PLillGF-RfqbYRpji8t4SxUkMxfowG4Kqp&index=1)




## Technologies
* Node.js
* Express
* Express Messages, Session, Connect Flash & Validation
* MongoDB & Mongoose
* Pug Templating
* Passport.js Authentication
* BCrypt Hashing

### Version
0.1.0

## Usage


### Installation

Install Mongo DB, tutorial on Windows install can be found [here](https://youtu.be/k_0ZzvHbNBQ?list=PLillGF-RfqbYRpji8t4SxUkMxfowG4Kqp&t=343)

On the MongoDB install/bin folder
```sh
$ mongod.exe --directoryperdb --dbpath C:/Path/to/Mongo/data/db --logpath C:/Path/to/Mongo/log/mongo.log --logappend --rest --install
```

Install the dependencies

```sh
$ npm install
```
Run app

```sh
$ npm start
```
