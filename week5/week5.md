 # week 5 homework
## Problem 26
a.Bob's claim is possible.So long as there exist enough peers in this torrent ,Bob can accept copy of file through optimistic unchoking.

b.the claim is also true.He can run a client on each host,let each cleint ”free ride".and combine the collected chunks from different hosts.

## Problem 28

a.if run TCPCLient before run TCPServer ,the client will try to establish a TCP connection with a non-existed server process.So the TCP connection will be failed.

b.because the UDP don't need to establish connection with Server.so it will go well if we run UDPClient first.And we need to give input.

c.If we use different port numbers.Then the client will try to establish a TCP connection with a  worng Server.Errors hanppen.