## Defintion of REST

- s a software architectural style which uses a subset of HTTP.

- It is commonly used to create interactive applications that use Web services.

- A Web service that follows these guidelines is called RESTful.

### Request basics
- A request can be initiated by invoking the appropriate method on the request object, then calling .then() (or .end() or await) to send the request.
- Old-style callbacks are also supported, but not recommended. Instead of `.then()` you can call `.end():`.
- DELETE, HEAD, PATCH, POST, and PUT requests can also be used,
- DELETE can be also called as `.del()` for compatibility with old IE where delete is a reserved word.

### GET requests
- The `.query()` method accepts objects, which when used with the GET method will form a query-string.

### Query strings
- req.query(obj) is a method which may be used to build up a query-string. For example populating `?format=json&dest=/login on a POST`.

### TLS options
* In Node.js SuperAgent supports methods to configure HTTPS requests:

- `.ca()` : Set the CA certificate(s) to trust.

- `.cert()` : Set the client certificate chain(s).

- `.key()` : Set the client private key(s).

- `.pfx()` : Set the client PFX or PKCS12 encoded private key and certificate chain.

- `.disableTLSCerts()` : Does not reject expired or invalid TLS certs.

