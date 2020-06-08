# summary class 11

## OAUTH2.0
is “an open standard for access delegation, example of Oauth (github, facebook and google).

is something like handshake it is work application spawns the “Login Using xxx” window, asking for specific permissions then user Agrees to allow this to happen, next remote service (i.e. Google) contacts the application with a one-time-use Code then the application calls back to a special address on the remote service to exchange that Code for a Token when the token has been granted, the application will then be able to contact the remote service, using that Token to access information on behalf of the user.

**the Token is User**

## Access Code
you need `<a>` tag  that will take them to the service’s authorization page.

## Roles
- The Third-Party Application: "Client"
- The API: "Resource Server"
- The Authorization Server
- The User: "Resource Owner"

## Creating an App
when creating new app, register basic information such as application name, website, a logo.