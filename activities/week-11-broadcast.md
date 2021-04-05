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

1. Give an example of a human protocol for sharing a broadcast medium
   (e.g., the air when we speak).

2. Would your example be most similar to a channel partitioning, random access,
   or turn-taking protocol?

3. Rank the following from worst to best scenarios for using a channel
   partitioning scheme.
   (You can rank some as a tie if they are roughly equivalent.)
   * Many senders, almost all sending
   * Few senders, almost all sending
   * Many senders, only one sending
   * Few senders, only one sending

4. What is the major downside to random access protocols?

5. Finish the sentence:
   A random access protocol will be the most effective type of protocol when...

6. In slotted ALOHA with `p = 0.5`,
   assume two senders send in the same slot,
   leading to a collision.
   What is the probability that there will be a collision between those senders
   in the next slot?
   What is the probability that the next slot will be wasted
   (either neither sends or both send)?

7. What is "carrier sense" and why is it helpful?

8. Why can collisions still occur when nodes are listening before they send?
   Is this more likely to occur with nodes that are near one another or far
   from one another?

9. What is wrong with the following description?

   Adding collision detection to CSMA increases efficiency by reducing the
   number of collisions between transmitting nodes.

10. Why is the backoff interval after a collision usually chosen randomly?

11. What is exponential backoff?
    Why can it be better than using a fixed set of choices for backoff
    intervals?

12. How are turn-taking protocols (e.g., polling) similar to TDMA?
    How are they different?

13. Compared to an IP address, a MAC address gives {more, less} information
    about a node's location.

14. What is one reason MAC addresses are useful when sending on a local network?
    In other words, why not just send directly to a certain IP address?

15. What is an ARP table?
    How are the entries in an ARP table determined?

16. Assume host `A` is on one network and host `B` is on a different network
    that is several hops away.
    Which of the following change during a packet's journey from `A` to `B`?
    (There is more than one possible answer depending on what assumptions you
    make.)
    * Source IP address
    * Destination IP address
    * Source MAC address
    * Destination MAC address
