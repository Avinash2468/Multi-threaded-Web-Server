# Multi Threaded Web Server with Usage Statistics

*Implemented as part of the operating systems & algorithms course at IIIT-Hyderabad during Monsoon 2021*.

- This project contains the code a multi-threaded web server. It also contains a report studying the effect of scheduling algorithms and number of threads on the response time and turnaround time of the server.

## Steps to run the code:

* run 'make' - this creates the executable ./target
* run './target SCHEDULING_POLICY' : SCHEDULING_POLICY = FIFO for first come first serve and SCHEDULING_POLICY = SFF for Shortest file first. Leave it running.
* run 'bash manyclients_ruby.bash' on a different terminal - this sends 90 requests to the server.
