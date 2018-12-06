# HTTP

* Hyper Text Transfer Protocol

* Build based on TCP protocol

* Maintain by W3 Consortium, http://www.w3.org/standards/techs/HTTP

# HTTP 1.0

# Three-way handshake, for every file.
* Start connection
* 1. Client sent a SYN (syn=i) package to server and running into SYN_SENT, waiting for response
        Synchronize Sequence Number.

* 2. Server receive the SYN package and identify the SYN (syn=i), sent a ACK package back to client (           ack=syn+1) and a SYN of the server (SYN=X), this package call SYN+ACK package, server running              into STN_RECV state.
        Acknowledgement

* 3. Client receive the SYN+ACK, sent an ACK (ack=x+1) to the server, after this one, client and server     running into ESTABLISHED state (TCP connected)
    End connection

# HTTP 1.1
* Persistent links
* Start connection
* Three-way handshake
* Data transmit
* End connection

* Host field
* Pipelining theory
* Chunked transfer-coding, Breakpoint renewal

![HTTP1](/assets/HTTP1.png)

# HTTP/ 2.0

![HTTP2](/assets/HTTP2.png)

* Publish at 2015, May

* HTTP/1.x using line break (换行符) to separate text. HTTP/2 using             smaller unit than HTTP/1.x, which are frame and Message

* Binary Framing

* Frame: The smallest unit of HTTP/2. Indicated which stream belongs to at the head of the Frame

* Message: One or more Frame
* Connection: Same as HTTP/1.x TCP connection
* Stream :Bidirectional byte stream (双向字节流) after connection

# Request and Response Multiplexing

![HTTP3](/assets/HTTP3.png)

* All process under one domain name could be finished by one channel.
* Bidirectional data flow
* Stream sent by Message format
* Each frame could be sent out of sequence transmission 
* Reduce multiple waste recourse caused by multiple TCP

# Stream priority

* In HTTP/2 each request could have an additional 31 bit priority value.

* 0 is the highest

# Server push

* Expect the regular request method, server allows to push additional           data to client.
* The additional data have own URL, can be cached by the browser.

* Client have right to reject the additional data.

* Use additional head of http to list what you need in the future. 
By analyzing the head of the http to pre-sent data in order to reduce time for loading.





