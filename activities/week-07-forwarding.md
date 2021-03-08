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

1. Is it easier to provide a minimum bandwidth guarantee in a packet-switched
or a circuit-switched network?
Why?

2. How do two hosts reserve bandwidth ahead of time in a packet-switched
network?

3. In which type of network, packet-switched or circuit-switched,
are queueing delays usually more of an issue?

4. Describe the difference between time-division and frequency-division
multiplexing.

In the next two questions, assume the network under consideration is
circuit-switched and uses TDM.

5. If there are 5 hosts sharing a 1 Mbps link
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

6. In the above question,
what percent of the time is the link idle?

7. If there are 5 hosts sharing a 1 Mbps link on a **packet-switched** network
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

8. When a packet moves from the input interface of a router to an output
interface,
this is... (forwarding or routing)?

9. List a few kinds of guarantees that could be provided by a network layer.
What guarantees are provided by the internet's network layer?

10. Where would queueing delays most likely occur in a router under each of the
following circumstances?
(Some of these may not result in excessive queueing at all.)
* The switching fabric is significantly slower than the input ports
* The switching fabric is significantly faster than the input ports
* The routing is done by a single routing processor instead of locally on each
  port

Consider the following routing table.
```
Destination address range           | Link interface
---                                 | ---
10100010 XXXXXXXX XXXXXXXX XXXXXXXX | 0
10100011 XXXXXXXX XXXXXXXX XXXXXXXX | 1
10100011 111XXXXX XXXXXXXX XXXXXXXX | 2
otherwise                           | 3
```
Give the link interface for each of the following addresses:
* 162.224.0.1
* 162.3.2.1
* 161.3.2.1
* 161.253.2.1

Note: `10100010b = 162`, `10100011b = 163`, and `11100000b = 224`.

11. Assume a router has 5 input ports and 5 output ports.
What is the maximum number of packets that can be moved across the switching
fabric at once using
* a bus?
* a crossbar?

For the next few questions, assume five packets arrive in the queue of an
output port of a router at roughly the same time.
We refer to the packets simply as 1, 2, 3, 4, 5, based on the order of their
arrival.

12. How will the packets be scheduled using priority scheduling if odd-numbered
packets are high-priority and even-numbered packets are low-priority?

13. How will the packets be scheduled using round robin scheduling if
packets 1 and 4 are one class and packets 2, 3, and 5 are another class?
