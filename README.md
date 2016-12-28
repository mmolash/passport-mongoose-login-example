# description
This is a sample web-based application that makes use of node.js, express.js, passport.js, and mongoDB to create a localized login platform.

To run the program, first install its dependencies with

`npm install`

Then, to obtain functionality, a create a file `/config/database.js` of the form:

```
module.exports = {
    'url':'mongodb://<user>:<password>@ds145188.mlab.com:45188/passport-mongoose-login-example'
};
```

if you are using a remote Mongo instance or add reference to your locally hosted database.

Finally, to launch the server, simply use
`node index.js`
in the directory.

This will start the server on port 8080.