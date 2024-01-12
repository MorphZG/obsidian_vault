---
tags: network protocol
---
# Notes from youtube

[The http and the web Request-Response cycle](https://www.youtube.com/watch?v=eesqK59rhGA)

- HyperText Transfer Protocol
- Application layer protocol that allows web-based applications to exchange data
- Based on TCP/IP (Transmission Control Protocol)
- HTTP is a connectionless protocol. After making the request, the client disconnects from the server. When the response is ready the server re-establish the connection again and deliver the response.
- It is also stateless. The client and the server knows about each other just during the current request. If it closes, and the two computers want to connect again, they need to provide full information to each other, connection is handled as the very first time
- Was designed for the web to fetch the html documents only but with time it was developed to move any type of data over the web in a quick and reliable way.

- http message have a 3 section structure: start line, headers, body (body can contain binary data).
- Information in each section vary, whether it is a request or response.
