## Welcome to CIS 457!

This is the main website for the course.
The slides, schedule, and links to assignments, labs, projects, and videos,
as well as the official course policies,
will be posted here.
The course also uses other websites for specific purposes.
* [Piazza](https://www.piazza.com/gvsu/winter2021/cis457/home) is a question-and-answer forum.
*All official announcements will be sent through Piazza*,
and you are responsible for monitoring Piazza to keep up to date with
announcements
(Piazza by default will send an email when an announcement is posted).
    * Signup link:
      [https://www.piazza.com/gvsu/winter2021/cis457](https://www.piazza.com/gvsu/winter2021/cis457).
    * You can read the following [Piazza FAQ](misc/piazza-faq.md) if you have
      questions.
* [Zoom](https://zoom.us) will be the video conferencing service for office
  hours and synchronous course meetings.
    * Course meetings and labs:
      [https://gvsu-edu.zoom.us/j/99095839766?pwd=eHZUbldONGg1UllaSTdqMHZMN3Vxdz09
](https://gvsu-edu.zoom.us/j/99095839766?pwd=eHZUbldONGg1UllaSTdqMHZMN3Vxdz09
)
    * Office hours:
      [https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09](https://gvsu-edu.zoom.us/j/98637553783?pwd=RzJsazNrcDhFemFRTCtvN2xiblFnUT09)
* [Prairielearn](https://prairielearn.engr.illinois.edu/pl/) is where you will
submit all of your assignments, labs, and projects.
* [ClassTranscribe](https://classtranscribe.illinois.edu/) is where the videos
will be hosted.

That seems like a lot to monitor,
but don't worry -- you really need only actively follow Piazza.
I will release announcements there any time assignments or videos are posted,
and I will post links to them directly on this page.

Be sure to read through the [syllabus](syllabus.md) for course policies,
contact information, and other important info.

## Schedule

** Note: This is an estimated timeline and subject to change. **

| Week | Topics | Readings | Deliverables |
| ---- | ------ | -------- | ------------ |
|  1   | Introduction to Networking<br>[intro slides](slides/intro-intro.pdf)<br>[network core slides](slides/intro-core.pdf)<br>[protocol stack slides](slides/intro-protocols.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=ebdb1fdc-4043-4830-bd71-efc229385333) | Chapter 1 | **Friday 1/22** [Syllabus quiz](https://prairielearn.engr.illinois.edu/pl/) |
|  2   | Application Layer<br>[application-layer intro slides](slides/app-intro.pdf)<br>[application-transport interface slides](slides/app-transport.pdf)<br>HTTP<br>[HTTP slides](slides/app-http-intro.pdf)<br>[HTTP format slides](slides/app-http-format.pdf)<br>[cookies slides](slides/app-http-cookies.pdf)<br>[delay slides](slides/intro-delay-intensity.pdf)<br>[throughput slides](slides/intro-throughput.pdf)<br>[web cache slides](slides/app-http-cache.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=296dd3bf-3e8c-457e-b44c-98498a10bb85)<br>[Monday activity](activities/week-01-intro.md) | 2.1-2.2 | **Monday 1/25** [Wireshark lab](https://prairielearn.engr.illinois.edu/pl/)<br>**Monday 1/25** [Lab partner survey](https://forms.gle/tkKudsEMCajn2vXAA) |
|  3   | Application Layer<br><br>DNS<br>[dns intro slides](slides/app-dns-intro.pdf)<br>[dns structure slides](slides/app-dns-architecture.pdf)<br>[dns protocol slides](slides/app-dns-protocol.pdf)<br>Email<br>[email intro slides](slides/app-smtp-intro.pdf)<br>[SMTP slides](slides/app-smtp-protocol.pdf)<br>[access protocol slides](slides/app-smtp-access.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=23cc90af-7ba4-48e5-8643-b1dd6bf2d6ca)<br>[Monday activity](activities/week-02-http.md) | 2.3-2.5, 2.7-2.8 | **Monday 2/1** [Lab 2 (HTTP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2309340) |
|  4   | Socket Programming<br>[socket programming slides](slides/app-socket.pdf)<br><br>Transport Layer<br>[multiplexing slides](slides/tr-multiplexing.pdf)<br>[UDP slides](slides/tr-udp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=a26da01d-d411-41af-ac59-822cd72d0f87)<br>[Monday activity](activities/week-03-dns-smtp.md) | 3.1-3.3 | **Monday 2/8** [Lab 3 (DNS)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2309535) |
|  5   | Transport Layer<br>[reliable data transfer slides](slides/tr-reliable.pdf)<br>[pipelined reliable transfer slides](slides/tr-pipeline.pdf)<br>[Go-Back-N slides](slides/tr-gbn.pdf)<br>[Selective Repeat slides](slides/tr-sr.pdf)<br>TCP<br>[TCP slides](slides/tr-tcp-general.pdf)<br>[sequence number and ACK slides](slides/tr-tcp-ack.pdf)<br>[reliable transfer in TCP slides](slides/tr-tcp-reliable.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=283bab64-c2c7-44de-bc95-33dcb5b66e6d)<br>[Monday activity](activities/week-04-transport.md) | | **Monday 2/15** [Lab 4 (Sockets)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2309650) |
|  6   | Transport Layer<br><br>TCP<br>[flow control slides](slides/tr-flow-control.pdf)<br>[TCP connection slides](slides/tr-connection.pdf)<br>TCP congestion control<br>[congestion slides](slides/tr-congestion.pdf)<br>[congestion control intro](slides/tr-cong-control-basics.pdf)<br>[congestion control policy](slides/tr-cong-control-policy.pdf)<br>[congestion control performance](slides/tr-cong-control-perf.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=9d94065b-83b9-45cd-8cd2-6925a71baea6)<br>[Monday activity](activities/week-05-reliable.md) | | |
|  7   | Network Layer<br>[switching](slides/intro-switching.pdf)<br>[network intro](slides/net-intro.pdf)<br>[routers](slides/net-routers.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=c4ef3fdd-5885-4e63-a2ff-76226211bc52)<br>[Monday activity](activities/week-06-tcp.md) | | **Monday 3/1** [Lab 5 (UDP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2309863)<br>**Friday 3/5** [Project 1 (FTP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2309750) |
|  8   | Network Layer<br>[IPv4](slides/net-datagram.pdf)<br>[Subnets](slides/net-addressing.pdf)<br>[DHCP](slides/net-dhcp.pdf)<br>[NAT](slides/net-nat.pdf)<br>[IPv6](slides/net-ipv6.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=fad1d787-6f4a-46e6-bff4-818e19e8eac9)<br>[Monday activity](activities/week-07-forwarding.md) | | **Monday 3/8** [Lab 6 (TCP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310028)<br>**Tuesday 3/9** Midterm Exam (during lab) |
|  9   | Network Layer (Routing)<br>[control plane intro](slides/net-control-intro.pdf)<br>[link state](slides/net-link-state.pdf)<br>[distance vector](slides/net-distance-vector.pdf)<br>[OSPF](slides/net-ospf.pdf)<br>[BGP](slides/net-bgp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=bef00e2a-1d46-4edd-9c83-de71441cb903)<br>[Monday activity](activities/week-08-network.md) | | **Friday 3/19** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310215) |
|  10  | Network Control and Management<br>[ICMP and SNMP](slides/net-management.pdf)<br><br>Link Layer<br>[intro](slides/link-intro.pdf)<br>[error detection](slides/link-error-detection.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=c3899d63-20ad-49d6-ae5c-4df98094b7c3)<br>[Monday activity](activities/week-09-routing.md) | | **Monday 3/22** [Lab 7 (IP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310242)<br>**Friday 3/26** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310329) |
|  11  | Link Layer -- Multiple Access<br>[TDMA and FDMA](slides/link-multiple-access-partition.pdf)<br>[ALOHA](slides/link-multiple-access-aloha.pdf)<br>[CSMA](slides/link-multiple-access-csma.pdf)<br>[taking turns](slides/link-multiple-access-turns.pdf)<br><br>MAC addressing and ARP<br>[MAC and ARP](slides/link-mac-arp.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=6d8db068-72a4-40dd-b99e-e65512dc27b1)<br>[Monday activity](activities/week-10-management.md) | | **Monday 3/29** [Project 2 (P2P)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310211)<br>**Friday 4/2** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310416) |
|  12  | Ethernet<br>[ethernet](slides/link-ethernet.pdf)<br>[switches](slides/link-switches.pdf)<br>[web request](slides/link-web-request.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=60791c57-82d0-4382-a24b-eaa8ce5aea85)<br>[Monday activity](activities/week-11-broadcast.md) | | **Monday 4/5** [Lab 8 (ICMP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310429)<br>**Friday 4/9** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310521) |
|  13  | Wireless and Mobile Networks<br>[intro](slides/wireless-intro.pdf)<br>[issues](slides/wireless-issues.pdf)<br>[CDMA](slides/wireless-cdma.pdf)<br>[WiFi (802.11)](slides/wireless-wifi-intro.pdf)<br>[CSMA/CA](slides/wireless-wifi-csma.pdf)<br>[802.11 frame](slides/wireless-wifi-frame.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=858c3622-1cbd-4e56-ab78-be765d53e582)<br>[Monday activity](activities/week-12-ethernet.md) | | **Monday 4/12** [Lab 9 (Ethernet and ARP)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310555)<br>**Friday 4/16** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310620) |
|  14  | Security<br>[intro](slides/security-intro.pdf)<br>[symmetric-key cryptography](slides/security-encryption-symmetric.pdf)<br>[public-key cryptography](slides/security-encryption-public.pdf)<br>[digital signatures](slides/security-digital-signature.pdf)<br>[securing email](slides/security-email.pdf)<br><br>[videos](https://classtranscribe.illinois.edu/offering/25085901-57c3-4816-bd31-47cb85cd70b8#plid=67a5e89a-be16-4038-aeeb-79bbc86e438a)<br>[Monday activity](activities/week-13-wireless.md) | | **Friday 4/23** [Optional activity upload](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310695)<br>**Friday 4/23** [Project 3 (Web Server)](https://www.prairielearn.org/pl/course_instance/128487/assessment/2310622) |
|  15  | **Final Exam**<br>Wednesday, April 28<br>10 AM - 11:50 AM Eastern | | |
