# Fullstack Assignment Server  <!-- omit in toc -->
This project setup to use [json-server](https://github.com/typicode/json-server). You will find a [db.json](./db.json) file that contains some data for the assignment.

# Table of Contents <!-- omit in toc -->
- [Pre-requisites](#pre-requisites)
- [Usage](#usage)
- [Documentation](#documentation)

# Pre-requisites
The following software is required to run this project
- [Node.js](https://nodejs.org)
- [Yarn](https://yarnpkg.com)

# Usage
To run the REST API server use the following command:

```sh
yarn start
```

Once running the expected output is:

```sh
$ curl -I http://localhost:3001/reservations
HTTP/1.1 200 OK
X-Powered-By: Express
Vary: Origin, Accept-Encoding
Access-Control-Allow-Credentials: true
Cache-Control: no-cache
Pragma: no-cache
Expires: -1
X-Content-Type-Options: nosniff
Content-Type: application/json; charset=utf-8
Content-Length: 2
ETag: W/"2-l9Fw4VUO7kr8CvBlt4zaMCqXZ0w"
Date: Fri, 12 Mar 2021 08:11:59 GMT
Connection: keep-alive
Keep-Alive: timeout=5
```

# Documentation
* [JSON Server documentation](https://github.com/typicode/json-server)
