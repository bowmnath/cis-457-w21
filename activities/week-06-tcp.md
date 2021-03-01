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

1. Why is a server generally able to handle more UDP clients at once than TCP
clients?

2. What, if anything, does a network do differently to support a
connection-oriented protocol like TCP vs a connection-less protocol like UDP?

3. Which of the following limit the maximum size of a TCP segment?
(There may be more than one.)
* The maximum size of an application message
* The maximum size of a network datagram
* The maximum size of a link frame

4. A TCP client sends a segment with sequence number 1000 and size 500,
and the server replies with a segment of size 800.
When the sender sends its next segment,
what will the sequence number be?

5. In the previous example,
the server would also use its reply to ACK the first segment from the sender.
What would the ACK number be?

6. Assume the expected RTT is computed using the formula from
[the slides](https://github.com/bowmnath/cis-457-w21/blob/master/slides/tr-tcp-ack.pdf)
with `a = 0.125` and that the initial estimation for RTT is 0.5 second.
The next two samples are 0.5 and 1 second, respectively.
* What is the new expected RTT?
* Would the expected RTT be different if the order of the two samples were
  switched?

7. Explain why flow control is used in TCP and how it differs from congestion
control.

8. The formula for determining whether a host can send data into the TCP
connection based on flow control is
```
LastByteSent - LastByteAcked <= rwnd
```
Explain in your own words
* what the left-hand side of the formula means,
* what the right-hand side of the formula means, and
* how this formula works to institute flow control.

9. Does the above formula apply to flow control in UDP?
Why or why not?

10. When closing a TCP connection,
the host that sends the final segment
(an ACK to the final FIN)
waits for a period of time before actually closing the connection.
Why is this done (i.e., what problem could arise if it were not done)?
If this step were skipped,
would there be any way for the other side to close the connection?

11. Describe the similarities and differences in the mechanism for
rate-limiting in flow control vs congestion control.

12. Why is a triple duplicate ACK treated differently than a timeout for
purposes of congestion control?
