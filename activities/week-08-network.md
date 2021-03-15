In your groups, answer the following questions.
As noted on Piazza,
you can turn in answers to this activity for extra credit on the midterm exam.
See the relevant Piazza note for details.

There is no need to rush through discussion to answer all of these on the day
of class --
any questions that we do not discuss will not be due as part of the extra
credit assignment for the week.
If you are not sure what needs to be filled out for a given week,
please feel free to ask.

I will be dropping in and out of rooms to facilitate to the discussions and in
case you have any questions.
Think of it like me walking around the classroom and listening to different
groups.
You can also flag me down in Zoom if you have a question even if I'm not in the
room
(I think the button in Zoom looks like a question mark).

Note: some questions are taken entirely or in part from your textbook.

# General Questions

This first set of questions is review from 7 material because we did not get to
it in our previous discussion,
so you may want to look in those lectures if you are searching for additional
information.

In the next two questions, assume the network under consideration is
circuit-switched and uses TDM.

1. If there are 5 hosts sharing a 1 Mbps link
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

2. If there are 5 hosts sharing a 1 Mbps link on a **packet-switched** network
and 4 of the hosts are almost always idle,
what is the effective transmission rate of the host that is sending?

3. Consider the following routing table.
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
* 163.253.2.1

Note: `10100010b = 162`, `10100011b = 163`, and `11100000b = 224`.

For the next few questions, assume five packets arrive in the queue of an
output port of a router at roughly the same time.
We refer to the packets simply as 1, 2, 3, 4, 5, based on the order of their
arrival.

4. How will the packets be scheduled using priority scheduling if odd-numbered
packets are high-priority and even-numbered packets are low-priority?

5. How will the packets be scheduled using round robin scheduling if
packets 1 and 4 are one class and packets 2, 3, and 5 are another class?

6. Explain the purpose of the time-to-live field in an IPv4 datagram header.
Why does including both this field and a checksum make IPv4 less efficient?

7. There are two ways that an IPv4 receiver can tell that a datagram it
receives is a fragment.
What are they?
Must both indications be present in every fragment?

8. Consider the host 223.1.4.8 on a subnet identified by 223.1.0.0/16.
Which part of the IP address specifies the subnet and which part specifies the
host on that subnet?
How many hosts can there be on that subnet?

9. Why is it important that DHCP requests and replies include a transaction ID?

10. Why are DHCP addresses leased as opposed to given permanently?

11. ISP A advertises that it services hosts 180.23.0.0/16.
ISP B advertises that it services hosts 180.23.17.0/24.
Where will packets to the following destinations be routed?
* 180.23.16.5
* 180.23.17.2

12. Consider a subnet 10.0.0.0/24 residing behind a NAT.
The internet-facing IP address of the gateway router is 270.33.9.4.
Host 10.0.0.2 sends a DNS query (port 53) to 138.75.90.2.
Give the source IP, source port, destination IP, and destination port of the
resulting IP datagrams at each of the following points.
If we do not have enough information to determine one of these numbers,
choose a random number that is sensible.
* DNS query while within subnet
* DNS query while in public internet
* DNS response while in public internet
* DNS response within subnet

13. Why is it possible (sort of) for two hosts on the internet to have the IP
address 192.168.2.2?

14. What is the main reason for the transition to IPv6?
Why might routers be able to handle IPv6 packets more efficiently than IPv4
packets?
