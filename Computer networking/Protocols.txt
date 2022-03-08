In networking, a protocol is a set of rules for formatting and processing data.


Web protocols ::

TCP/IP :
HTTP
DHCP
FTP
SMTP
Pop3 and imac (to recieve mail)
SSH
VNC
Telnet

Sockets
Ports 


1. HTTP (Hypertext transfer protocol) ::

HTTP uses TCP.

Get Post Put Delete

HTTP methods :
1. Get
2. Post
3. Put
4. Delete

List of HTTP Status Codes ::

1xx informational response
An informational response indicates that the request was recieved and understood .

2xx success


3xx redirection
This class of status code indicates the client must take additional action to complete the request .

4xx client errors
400 Bad request
402 Payment Required
403 Forbidden
404 Not found

5xx server errors
The server failed to fulfil a request .

Unofficial Codes ::

419 Page expired
420 Method Failure
etc .

HTTP cookies (also called web cookies , internet cookies , browser cookies or simply cookies) are small blocks of data 
created by a web browser while user is browsing a website .
Cookies : unique String 
Stored in my browser . ?????

Third party Cookies


How email works ?
SMTP : SIMPLE MAIL TRANFER PROTOCOL  (sender)
POP3 : Post Office Protocol (reciever)
IMAP

DNS (Domain name System)
mail.google.com 

mail :: sub-domain
google :: second-level domain
com :: top level domain

Root DNS servers

.io                  .org               .com    < Top level domain
Student.io      computer.org         google.com  < sub level domain

icann
icann.org

root-server.org

dig command

CheckSums :: A checksum is a small-sized block of data derived from another block of digital data for the
purpose of detecting errors that may have been introduced during its transmission or storage .

TCP Timers :: 

UDP (User datagram protocol)

Data may or may not be delivered
Data may change
Data may not be in order .

conectionless protocol 
UDP uses checksum .

UDP packet

uses
it is very fast 
video conferencing
DNS -> UDP
gaming

sudo tcpdump -c 5


TCP (transmission control protocol)
Tansport layer protocol
application layer lots of raw data .

3-way handshake .
