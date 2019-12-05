The goal was to create HTTP requests and HTTP responses. This code sends a request to an http server using a socket's output stream; then it reads the response using the socket's input stream. HTTP servers close the connection when they've sent the response. I have implemented GET and PUT requests in client so requestor can either get a html request or can put a html request.

Process of Running:

First we compile both HTTPServer.java and HTTPClient.java
We run server first using “java HTTPServer [port]”
Using another terminal we run client “java HTTPClient [host] [port] GET/PUT filename”
