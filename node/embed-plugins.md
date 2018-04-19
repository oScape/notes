# Embed plugins nodejs


## Server

- HTTP
> Create HTTP server

```
var http = require('http');
var server = http.createServer(function(req, res){ ... });
```

- URL
> Get HTTP request url

```
var url = require('url');
var page = url.parse(req.url).pathname;
```

- Querystring
> Get parameters in HTTP request url

```
var querystring = require('querystring');
var params = querystring.parse(url.parse(req.url).query);
```

- EventEmitter
> Get parameters in HTTP request url

```
var EventEmitter = require('events').EventEmitter;
var params = qs.parse(url.parse(req.url).query);
```
