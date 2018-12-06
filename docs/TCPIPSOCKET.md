#TCP/IP Socket

A socket programming interface provides the routines required for interprocess communication between applications, either on the local system or spread in a distributed, TCP/IP based network environment. Once a peer-to-peer connection is established, a socket descriptor is used to uniquely identify the connection. The socket descriptor itself is a task specific numerical value.

One end of a peer-to-peer connection of a TCP/IP based distributed network application described by a socket is uniquely defined by
* Internet address

for example 127.0.0.1 (in an IPv4 network) or FF01::101 (in an IPv6 network).

* Communication protocol

* User Datagram Protocol (UDP)

* Transmission Control Protocol (TCP)

* Port

A numerical value, identifying an application. We distinguish between

* "well known" ports, for example port 23 for Telnet

* user defined ports
