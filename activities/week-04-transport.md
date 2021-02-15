In your groups, answer the following questions.
No need to report the answers to me --
this is just for practice.
We may not get through all of the questions every week.
You may want to take notes during the discussion,
because these questions will be helpful in reviewing for exams.

I will be dropping in and out of rooms to facilitate to the discussions and in
case you have any questions.
Think of it like me walking around the classroom and listening to different
groups.
Again, this isn't meant to be for a grade,
so don't be concerned about giving a wrong answer even if I am in the room.
You can also flag me down in Zoom if you have a question even if I'm not in the
room
(I think the button in Zoom looks like a question mark).

Note: some questions are taken entirely or in part from your textbook.

# General Questions

1. Explain the purpose of a "welcome" socket vs a "connection" socket in TCP.

2. What is the difference between a UDP welcome socket vs a TCP welcome
socket?

3. If my client encodes strings using UTF-8 and my server decodes them using
ASCII,
will this be a problem?
Why or why not?
(This is not a question about those two particular encodings.)

4. HTTP and SMTP both run over TCP.
However, those two protocols have substantial differences in the messages they
send.
How do these differences affect the transport-layer headers?

5. If UDP were to change the way it computed a checksum,
would routers on the internet need to be updated accordingly?
If so, how?
If not, why not?

6. When a simple application message,
such as an HTTP GET request,
is sent from a client to a server,
is the message largest when it is
* an application-layer message,
* a transport-layer segment, or
* a network-layer datagram?
Why?

7. We will study encryption later,
but a simple understanding is that it allows messages to be passed privately
between processes even in the presence of eavesdroppers.
Why might it be helpful to provide encryption at the transport layer rather
than the application layer?
What downsides might there be?

8. Assume an internet-connected host runs just one networked application.
For example, this host is only a web server.
Since there is no problem distinguishing which application messages are being
sent to,
can this server get by without implementing transport-layer protocols?
Why or why not?

9. What is the purpose of port numbers?
How do they differ from IP addresses?

10. Servers generally listen on well-known port numbers,
such as port 80 for an HTTP server.
Why do clients not need to send from well-known numbers?

11. If I know a TCP segment was sent to (192.168.3.1, 80),
is that enough information to specify which socket it goes to?
Why or why not?

12. In UDP, only the destination IP and port are necessary to specify a socket.
If two clients send UDP segments to the same (IP, port) pair,
why are they not interfering with one another's connections?

13. Why might using UDP as the transport protocol for a video streaming service
be frowned upon?

14. Ethernet is a link-layer protocol that provides error detection at the link
level.
If my computer is connected to my router via Ethernet,
why might a UDP checksum still prove helpful?

15. At the receiving host,
the sum of 16-bit words in a message is
```
0110011001100000
```
and the UDP checksum is
```
0001100110011111
```
Did an error occur in the transmission?
