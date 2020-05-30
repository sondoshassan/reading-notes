# summary class 06

## HTTP
is a Hyper Text Transfer Protocol. the client make a request. HTTP associated with `html`,`.json` and `.xml`.

TCP(Transmission Control Protocol). the command line of request includes *method*, *URL* and *HTTp version*. and contains header and optional body.

Safe method used for retrival infomation and not change on server state. Idempotent identical request should get an identical response. Cacheable the client able to cach the response.

The response contains *HTTP VERSION*, *STATUS CODE* and *STATUS MESSAGE*.

## REST
use amethod which called verbs. and using HTTp as a transfer protocol.


REST Method |	CRUD 
--------|---------
GET	| READ
POST | CREATE
PUT | UPDATE	
PATCH | UPDATE	
DESTROY | DELETE

## Swagger
is open API. is a documentation talkin about how u can use this API.
API can written by `.yml` or `.json`.

### Swagger tools include
Swagger Editor – browser-based editor to write OpenAPI specs.
Swagger UI – renders OpenAPI specs as interactive API documentation.
Swagger Codegen – generates server stubs and client libraries from an OpenAPI spec.