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

1. Assume all physical media involved and all ethernet adapters involved on a
   particular subnet run 100 Mbps ethernet.
   Which will generally result in a higher effective throughput on the subnet?
   * bus-based ethernet
   * switched ethernet

   Why?

2. Ethernet includes a cylcic redundancy check for bit errors.
   Given that, is ethernet considered a reliable protocol?
   Why or why not?

3. What is the purpose of the `type` field in the ethernet header?
   What would be the analogous field in a transport layer header?

4. Ethernet can be considered both a ____-layer and a ____-layer protocol.

For the next few questions,
consider the following image taken from the slides provided by the textbook
authors.
Note that the hosts are connected via a *switch*,
not a router.

![switched ethernet](images/switched-ethernet.png)

5. Consider the following statement:

   Before host A can send to host C,
   it must learn the MAC address of interface 1 of the switch.

   If this is true,
   how does A learn the MAC address?
   If not, why not?

6. Assume all other hosts want to send to A at the same time.
   If the network is running 100 Mbps ethernet,
   what is the rate at which data is received by A?

7. Give a few similarities and differences between a switch table and a routing
   table.

8. In the diagram above,
   if B wanted to read frames meant for A,
   how could it trick the switch into sending those frames to B?

9. Assume the switching table for the network above is initially empty.
   Host A sends to host B, then host B sends to host C.
   What does the switching table look like after this process is complete?

10. Give a disadvantage of having a very large switched-ethernet LAN.

11. Explain in your own words what a VLAN is.
