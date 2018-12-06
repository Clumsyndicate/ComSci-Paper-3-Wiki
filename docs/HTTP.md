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
