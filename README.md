# Creating a web server FROM SCRATCH (kinda)

Have you ever wondered what is going on behind the scenes when you create a web
server using a high level framework like Express?

```javascript
const express = require('express');

const app = express();
app.get('/', (req, res) => {
    req.status(200).send("Easy profit");
});
```

If you do, wouldn't it be great if you could build a web sever from scratch and
finally see just **HOW MUCH** is being abstracted away by those fashionable
frameworks?

For some strange reason, I thought that it would be a fun idea to give it a
shot. Hopefully, I'll get to pick up some nifty new skills along the way too and
brush up on my networking knowledge.

## Rules

* The web server should be a HTTP server.
* No libraries allowed, but I'll be able to use APIs provided by
  the operating system like sockets.
* The code should not become a steaming hot pile of mess, it should be readable
  and kept organized.
* The web server should support basic HTTP methods like `GET`, `PUT`, `POST` and
  `DELETE`.
* The web server should automatically handle basic HTTP headers like
  `connection`, `keep-Alive`, etc. Ok I'll have to read up more.

## Ideas

* Good chance to learn a new low-level language like Rust?

## TODOS

* Go through some RUST tutorials
* Pray that RUST has a good socket library
* Decide on language
* Familiarize myself with the HTTP specs and figure out which parts to implement

