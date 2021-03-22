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

1. Explain the relationship between forwarding and routing.

2. What are some different criteria that might be used in determining which
   path to take through the network?

3. What is the difference between static and dynamic routing?
   Give an advantage and disadvantage of each.

4. Consider a router that knows the minimum distance from each of its neighbors
   to each end host on the system.
   That router is running a... (link state or distance vector)
   ...routing algorithm.

5. Running Dijkstra's algorithm with node `u` as the starting point results in
   the following table of distances and predecessors in the format used in the
   lecture video once the algorithm has finished.
   ```
   | v   | w   | x   | y   | z   |
   | --- | --- | --- | --- | --- |
   | 5,z | 2,u | 3,u | 9,x | 4,w |
   ```
   What is the least-cost path from `u` to `v`?
   What is the cost of that path?

6. Using the results above,
   write out the forwarding table for the router `u`.

7. Which of the following could be sensible choices to use as link costs?
   * Physical distance
   * 1/(Physical distance)
   * Congestion
   * Link bandwidth
   * 1/(Link bandwidth)

8. Explain how using current congestion to determine link weights can cause an
   algorithm to fail if it is not implemented carefully.

9. Consider a three-router network with routers `A`, `B`, and `C`.
   The initial distance vector for `A` is given below.
   ```
   |    | A   | B   | C   |
   | ---| --- | --- | --- |
   |  A | 0   | 5   | 2   |
   ```
   `A` then receives these two distance vectors from its neighbors.
   ```
   |    | A   | B   | C   |
   | ---| --- | --- | --- |
   |  B | 5   | 0   | 1   |
   |  C | 2   | 1   | 0   |
   ```
   What is the updated distance vector for `A`?

10. Why is it useful to have different protocols for intra-AS vs inter-AS
   routing?

11. Why is it useful for OSPF to authenticate its messages?

12. In your own words, what do the `AS-PATH` and `NEXT-HOP` attributes of BGP
   messages mean?
   Why are they important?

13. Consider routing a packet to a distant prefix `X`.
   For each of the following, state whether it is the responsibility of BGP
   or OSPF.
   * Determining which ASes packet will go through along the way.
   * Determining which gateway router with local AS packet should be sent to.
   * Determining which outgoing link is used to forward packets toward gateway
     router.

14. Explain a few ways in which pure hot-potato routing,
   without consideration of the other factors that go into BGP route selection,
   could lead to a "bad" choice of path.
