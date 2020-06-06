# summary class 11

## User Modeling
 The improtant data like passward and email must be encrypted by using hashing algorthim before saved it to DB. this prevent anyone to access data base including the developer.

 ## Cryptography

 is a method to encode the massage just the persone who now the secrete information can access this massage.

 ## Hash Algorthim 

 in user model, a hash password stored when the user sign up. then when the user want to sgin in send the user send password and the server hash login password. then the server can compare between the login password and the stored password  to determine if the user should be authenticated.

 ## Cypher Algorithms

 this algorthim takes a piece of data and a key to produce as encrypted data. then this data reversed into original data by decrypting by same key.
 tokenSeed (is a random unique string). the server can reverse the token in the tokenSeed by decrypting.

## Basic Authorization

btoa ==> for username
atob ==> for bassword
encode to encrypted the password but decode to return the password. encoded by using base64.

#### Protocol
- server side:
server wants the user to authenticate itself towards the server, the server must respond appropriately to unauthenticated requests. To unauthenticated requests, the server should return a response whose header contains a HTTP 401.
- client side:
when the user send authentication to the server, it may use the Authorization field.
The authorization field is constructed as username and password are combined with a single colon (:) and resulting string is encoded using a variant of Base64.

## JSON web token (JWT)
 is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.
 you use it in *Authorization* when the user logged in, the request will include JWT, allowing the user to access routes, services, and resources. Another used fo JWT is *Information Exchange* .
 is consist three parts sperate by dot (.) are header(consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA), payload and signature ( you have to take the encoded header, the encoded payload, a secret, the algorithm specified in the header, and sign that).

 The content of header should look like: `Authorization: Bearer <token>`.

 If the token is sent in the Authorization header, Cross-Origin Resource Sharing (CORS) won't be an issue as it doesn't use cookies.

 when using JWT the ecoded is smaller and make Jwt more compact than SMAl(Security Assertion Markup Language Tokens).