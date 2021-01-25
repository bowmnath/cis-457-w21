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

1. Give an example of a protocol that people use in everyday life to
communicate with one another.
Are there ways in which people can deviate from the protocol?
If so, what happens?

2. When connecting two computers, do you believe it is necessary to have a
packet switch between them?

3. We will soon be learning how email is implemented.
Do you expect it will be implemented in the network core or at the network
edge? Why?

4. Do network layer protocols need to be implemented differently on nodes that
are connected via Ethernet vs nodes that are connected via WiFi?
Why or why not?

5. A professor at University of Atlantis just invented a brilliant network
protocol that will make routing messages much more efficient.
Atlantis replaces all of their internet-connected devices with ones that run
the new protocol.
Will the underwater citizens see significant improvement to their Netflix
download speeds?
Why or why not?

6. What is the purpose of the IETF and the RFCs that they publish?

For the next few questions, assume all links have a transmission rate of 1000
bits/second.
Also, assume there is no other traffic on the network and that propogation
delay is negligible.

7. Host A is connected to host B via a path containing 4 routers.
Assume a single packet is up to 1000 bits in size.
How long will it take for A to transmit 1000 bits to B?

8. Same setup as the previous question,
but a single packet can now be up to 500 bits in size.
How long will it take for A to transmit 1000 bits to B?
(We did not do one exactly like this in lecture;
do your best to puzzle it out.)

9. From your work above,
can you generalize how long it takes to send
    * P packets,
    * each of length L bits,
    * over N links (N - 1 routers)
    * that have transmission rate R bits/second?

10. Why is packet loss to be expected in a congested network?

11. An application is sending message *m* to another application.
Header information will need to be added and removed as the message makes its
way through the network.
When will the message be larger:
when it is handled by the link layer,
when it is handled by the transport layer,
or it will be the same size in both cases?
Why?

12. TCP offers guaranteed delivery of any message.
Why does UDP, the other transport-layer protocol,
still exist even though it does not have that feature?
