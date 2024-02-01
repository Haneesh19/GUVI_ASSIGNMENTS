# A blog on Difference between HTTP1.1 vs HTTP2 #   
## HTTP ##   
* HTTP Stand for Hyper Text Transfer Protocol.
* It is used for the communication between the server and client.
* The HTTP protocol is used to send the request by the user to server and server responds to the user.   
* HTTP2 is the updated version pf HHTP1.1 to overcome its flaws.   
## HTTP1.1 ##   
* HTTP1.1 is created in 1997.   
* It works on textual format.   
* It loads resources one after the other, so if one resource cannot be loaded, it  will block all the other resources behind it.   
* It send multiple streams of data at once so the other resource blocks any other resources.   
* Small files load more quickly than large ones. To speed up web performance the HTTP1.1 protocol compress the files by itself.   
## HTTP2 ##   
* HTTP2 is created in 2015   
* It works on binary protocol.   
* It uses a single TCP connection  which send multiple streams of data at once so that no one resource blocks any other resources.   
* It uses PUSH frame by server that collects all multiple pages .   
* HTTP2 protocol uses an advanced compression method called HPACK to compressthe file.It compress effectively than HTTP1.1.   
