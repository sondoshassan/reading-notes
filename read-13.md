# summary class 13

## Sending form data
### Client/server architecture
a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

### the client side
in the form the method maybe will be GET or POST. 

After submitting the form:

Open the developer tools.
Select "Network"
Select "All"
Select "foo.com" in the "Name" tab
Select "Headers"

POST can be very important for two reasons:

- If you need to send a password (or any other sensitive piece of data), never use the GET method or you risk displaying it in the URL bar, which would be very insecure.
- If you need to send a large amount of data, the POST method is preferred because some browsers limit the sizes of URLs. In addition, many servers limit the length of URLs they accept.

## HTML5 form
- button
- fieldset: a group of controls
- form: an interactive form
- input: an interactive control
- legend: a caption
- textarea: a multi-line text control 
