## TCP Three Way Handshake

- Reference: [Ref1](http://www.techopedia.com/definition/10339/three-way-handshake)

### Intro
- The TCP three-way handshake is the method used by TCP to set up a TCP/IP connection over an Internet Protocol based network.
- It is a three-step method that requires both the client and server to exchange SYN and ACK.

### Objective
- Two computers attempting to communicate can negotiate the parameters of the network TCP socket connection before transmitting data such as SSH and HTTP web browser requests.
- Both ends can negotiate seperate TCP socket connection at the same time. 
  - Being able to negotiate multiple TCP socket connections in both direction at the same time allows a single physical network inferface, such as ethernet, to be multiplexied to transfer multiple streams of TCP data simulteneously.
  
### How it works

