# JS-SHARE

![JS-Share](https://github.com/js-share/js-share/blob/master/client/public/logo.png)

### The most advanced real time collaboration platform ever created.

Utilizing Google Authentication to verify all users, you will be able to access your own documents while also sharing documents with other users that have signed up.
 
  - Make sure you have the .env file when running the server locally
  - Google OAuth is requrired for you to create and share documents
  - Update code and run it right in the browser

##### New Features!

  - Clean styling using bootstrap 4.0 with minimal CSS
  - Auto-user sharing by typing in multiple valid email addresses

##### You can also:
  - Copy and paste code and run it right in the console and then save it to your personal document within the custom PostgresQL database.  
 
### Steps to get local server running

> npm install from client folder first
> npm install from root/server directory
> npm run dev from root/server directory (make sure .env file is present) 
 
### Tech
 
* [Node Express] - Secure JS Server software!
* [Passport & GoogleOAuth] - leave authentication to the other people
* [Postgress] - ACID compliant database structure for storing and retrieving documents for users
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework 
* [Webpack] - the streaming build system 
* [axios] - fastest API requests in the west 
 
### Development

JS-Share uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ npm install
```

Second Tab:
```sh
$ npm install /client/package.json
```

(optional) Third:
```sh
$ npm run dev
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
localhost:3000
``` 

### Todos

 - Write MORE Tests
 - Add Night Mode

License
----

MIT

 
