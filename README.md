# Example
Node JS most famous framework is`Express`. Many developer recommends `express` framework to write the back-end code. People are using express because it is `customizable backend scripting language`, code can be written in pure js (ES5 or ES6), now today's world we can also write back-end code by using typescript.

In this project we will use swagger routes with middlewares. It makes our API documentation much more attractive and understandable. So any one back-end developer can understand, what's going on.

## Requirment
`Mongodb 4.0+`
+ **Install MonngDB 4.0+**
+ *` Ref: `* https://docs.mongodb.com/manual/installation/
+ **Connetion String** (mongodb://<username>>:<password>@localhost:27017/example) 

`NodeJS v8+`
+ *`Ref:`* [Learn Node](http://nodejs.org)
+ Framework: [Learn Express](https://expressjs.com/)

## Run Locally with Node
+ Clone the project:
+   ```https://<username>@bitbucket.org/webzoolll/rspbackend.git```
+ Go to project working directory / Project folder
+ Execute command   `npm install`
+ After that Run Command `npm start`
+ Open `http://localhost:4007` to check that your server is running or not.

##### Set environment variable
- No need to set custom environment variable, if you want to set any environment variable just add it to `.env` file.
- Set port by writing one line PORT=4007 for running server, there is no default port available in code so you need to set PORT.
- config -> .env_sample will let you know about the system variables which this project requires
- There is a `npm module` called `dotenv` will configure environment variable from `.env` to our system. `.env` is the default environment file which will automatically configured by the `dotenv`;
- You need to require `dotenv` on the to of the index.js file
- i.e `require('dotenv').config()`


## Thank you
