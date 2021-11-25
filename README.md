### Multi Threading Web Server

#### Steps to run the code:

* run 'make' - this creates the executable ./target
* run './target SCHEDULING_POLICY' : SCHEDULING_POLICY = FIFO for first come first serve and SCHEDULING_POLICY = SFF for Shortest file first. Leave it running.
* run 'bash manyclients_ruby.bash' on a different terminal - this sends 90 requests to the server.