# summary class 11

## Bearer Authentication
are encoded `JSON objects` that *bear* or *contain* enough information for the server to assert that any client request that presents a valid token must have originated from a client that has previously authenticated themselves using either Basic or OAuth.

## JSON Web Tokens
 is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
 you use it in *Authorization* when the user logged in, the request will include JWT, allowing the user to access routes, services, and resources. Another used fo JWT is *Information Exchange* .
 is consist three parts sperate by dot (.) are header(consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA), payload and signature ( you have to take the encoded header, the encoded payload, a secret, the algorithm specified in the header, and sign that).

 The content of header should look like: `Authorization: Bearer <token>`.

 If the token is sent in the Authorization header, Cross-Origin Resource Sharing (CORS) won't be an issue as it doesn't use cookies.

 when using JWT the ecoded is smaller and make Jwt more compact than SMAl(Security Assertion Markup Language Tokens).