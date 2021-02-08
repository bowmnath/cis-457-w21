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

1. What is the difference between an NS record and an A record in DNS?
If I have an NS record for a nameserver,
do I also need an A record for that same server?

2. If I want to email `student1@mail.gvsu.edu`, `student2@mail.gvsu.edu`,
and `prof@gvsu.edu`,
how many MX records do I need?
How many A records?

3. Which of these will cause a larger increase in records that must be stored
at the root DNS servers?
    * 500 new websites of the form `*.com`
    * Creating a new `.supergood` TLD that currently holds 50 websites

4. You become the proud owner of `457isthebest.com`.
What do you need to do to register `i.think.457isthebest.com`?

5. Assume your local DNS server has the `gvsu.edu` NS record cached.
If you visit `cis.gvsu.edu/~bowmnath/index.html`,
how many DNS requests will your server need to make
(ones that it cannot satisfy from its cache)?

6. What is the difference between an MX record for `gvsu.edu` and an A record
for `gvsu.edu`?
If I have an MX record,
do I have all the information I need to contact the `gvsu.edu` mail server?

7. A recursive DNS request results in the client sending fewer DNS messages
for a particular query.
Why would a client ever *not* request a recursive query?

8. What is the purpose of the TTL field in DNS RRs?

Switching gears to email...

9. Does a user agent need to understand SMTP?
Why or why not?

10. What is the advantage to using a dedicated mail server rather than sending
email directly from a user agent?

11. Can you think of any reason an SMTP handshake is helpful?
Once the TCP connection is established,
why not just send the first email?

12. Based on what you saw in lecture,
how does SMTP prevent email spoofing
(sending email from someone else's address)?

13. Describe what it means that SMTP is a push protocol whereas HTTP is a pull
protocol.
