# Ionic4 CRUD

Use API from [Node.js, Express.js, Sequelize.js and PostgreSQL RESTful API](https://www.djamware.com/post/5b56a6cc80aca707dd4f65a9/nodejs-expressjs-sequelizejs-and-postgresql-restful-api) tutorial.

If you have the problem when running this app to simulator or device. `ERROR: Backend returned code 0, body was: [object XMLHttpRequestProgressEvent]`
Try removing the `WKWebView` by type this command.
```
ionic cordova plugin rm cordova-plugin-ionic-webview
```