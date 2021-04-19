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

1. The primary differences between wired and wireless networks occur at which
   layer(s)?

2. What is an ad-hoc network?
   How does it differ from most of the wireless networks we discuss?

3. If a network has a low signal-to-noise ratio (SNR),
   should it use a high-bitrate or low-bitrate modulation scheme?

4. What is a beacon frame in an 802.11 network and what purpose does it serve?

5. If a wireless sender could send and receive at the same time,
   would this allow collision detection to be effective in a wireless setting?
   Why or why not?

6. Consider hosts A and B using CDMA with the following chipping sequences:
   ```
   A: 1  1  1 -1  1 -1 -1  1
   B: 1 -1  1  1  1 -1  1 -1
   ```

   A receiver receives the following signal in one time slot:
   ```
   2 0 2 0 2 -2 0 0
   ```
   What was the bit sent by A?

7. Consider both CSMA/CD and CSMA/CA.
   For each of these protocols,
   state whether each of the following conditions would cause an exponential
   backoff.
   Some of these do not make sense for one of the protocols --
   if that is the case, explain why.
   * Sender has data to send, but senses channel is busy
   * Sender detects collision while sending frame
   * ACK is not received after sending frame

8. Assume a wireless host has MAC address 11:22:33:44:55:66.
   The addresses in an 802.11 frame are, in the following order,
   * AA:BB:CC:DD:EE:FF
   * 11:22:33:44:55:66
   * 12:34:56:78:9A:BC

   What is the MAC address of the router?
   Is this frame going from router to host or host to router?

9. To get all the way from a wireless host to a router,
   a packet will go through both an 802.11 frame and an 802.3 frame.
   Why?

10. Consider a host that changes access points but remains on the same subnet.
    Which of the following change?
    * IP address of host
    * MAC address of host
    * MAC address of associated access point
    * MAC address of router

11. Explain how a wireless host that is not very active
    (i.e., does not send or receive very many packets)
    can save battery life.
