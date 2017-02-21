# psadvnode
##2.Node!=JavaScript
###3 Node's Architecture: V8 and libuv
```
node --v8-options
node --harmony_trailing_commas -p 'function t(a,b,){}'
```

##6. Node for Web
###1 The Basic Streaming HTTP Server
```
curl -i localhost:3000
```

###2 Working with HTTPS
```
openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -nodes
```


###3 Requesting HTTP/HTTPS Data
for client
```
req = http.ClientRequest
```
for server
```
req = http.IncomingMessage
res = http.ServerResponse
```

##7. Node's Common Built-in Libraries
###1 Working with the Opening System
```
os.constants.signals
```
