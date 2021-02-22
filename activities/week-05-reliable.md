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

1. What mechanism is used to detect corrupt packets in TCP?

2. What mechanism is used to detect lost packets in TCP?

3. Can you think of any other way to detect lost packets than the mechanism
described in (2)?
If so, explain.
If not, why not?

4. Describe what is meant by a "stop-and-wait" protocol.

5. Assume there is a communication channel that does *not* corrupt packets,
but that may lose packets.
If a stop-and-wait protocol is employed,
are sequence numbers necessary?
If so, come up with a scenario where the protocol would fail without sequence
numbers.
If not, explain why not.

For the next two questions, assume the following scenario:
Using GBN with a window size of 5, a sender sends packets 1 - 5.
The sender recieves just one ACK, and the ACK is for packet 3.

6. Which packet(s) will be re-sent?

7. What is the current window for the sender?

8. Assume a TCP sender sends packets 1 - 5 and receives ACKs for 1, 4, and 5.
What packet(s) will be re-sent?

9. In lecture, our assumption was that packets would not "switch order" in
the network.
That is, if packet A is sent before packet B,
packet A will arrive before packet B unless packet A is lost.
If we get rid of this assumption,
do we need to make any changes to rdt3.0 to account for it?
If so, describe the changes.
If not, explain why.

10. Which will benefit more from pipelined data transfer:
* connection with low latency and high transmission rate, or
* connection with high latency and high transmission rate?

Why?

11. Assume a receiver has a very small receive buffer.
Which protocol would likely be a better fit: GBN or SR?
Why?

12. Assume an SR sender has a window size of 5 and sequence numbers [0 - 7].
Explain why this combination fo sequence numbers and window size would not work
using an example.
I.e., come up with a scenario in which the receiver does not know whether it is
receiving new or old data.

13. Assume the same scenario as the previous problem,
but using GBN instead of SR.
Could the same problem arise?
Why or why not?
