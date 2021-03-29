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

1. Explain a few ways in which pure hot-potato routing,
   without consideration of the other factors that go into BGP route selection,
   could lead to a "bad" choice of path.

2. What is the general purpose of ICMP?

3. Although ICMP runs on top of IP,
   it is not considered part of the transport layer.
   Why not?

4. Now that you know about ICMP,
   briefly explain how `ping` works.

5. What is the difference between SNMP in request/response mode vs trap mode?
   (The purpose, not the header information.)

6. Give an analogy to explain the difference between the link and network
   layers.
   One that is at least slightly different from the analogy in the lecture
   video would be preferable.

7. Which of the following need to run link layer protocols?
    * Gateway router
    * Backbone router
    * Web client
    * Web server

8. Consider the high-level description of error detection below.
   What is wrong with this description?

   The sender appends extra bits to the message according to some agreed-upon
   rule.
   The receiver receives the original message plus the extra bits.
   It then runs an algorithm to determine whether the received versions of the
   message and extra bits match.
   If the receiver confirms the received frame is identical to the original,
   it passes the payload up to the next layer.
   Otherwise, it discards the frame.

9. Consider parity-checking system where parity bit ensures sum is odd.
   A sender sends the following (`message | parity bit`).

   ```
   11001100 | 1
   ```

   If the receiver receives the following, what happens?

   ```
   11000000 | 1
   ````

10. Assume we are using a two-dimensional parity where the parity bit ensures
    the sum is odd.
    (Note that this is different from the two-dimensional parity scheme
    described in the slides.)
    The received message below contains a single bit error.
    Correct the error.

    ```
    1 1 0 0 | 1
    0 0 1 0 | 0
    1 1 1 0 | 1
    1 1 1 1 | 1
    -----------
    0 1 0 0 | 0
    ```

11. Using a cyclic redundancy check with the generator `1101`,
    append the three-bit value `R` to the message `1011010`.
    You can check your answer by performing the CRC as the receiver using your
    determined value of R.

    <!--
    Compute R:
    ```
              1100 100
    1101 | 1011010 000
           1101
            1100
            1101
             0011
             0000
              0110
              0000
               110 0
               110 1
                00 10
                00 00
                 0 100
                 0 000
                   100  <-- answer
    ```

    Check:
    ```
              1100 100
    1101 | 1011010 100
           1101
            1100
            1101
             0011
             0000
              0110
              0000
               110 1
               110 1
                00 00
                00 00
                 0 000
                 0 000
                   000  <-- verified
    ```
    -->
