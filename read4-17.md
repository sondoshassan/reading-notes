# summary class 17


## OSI Model
Open Systems Interconnection Reference Model, we have a seven layers model but not all used for example HTTP skips the Presentation and Session layers and lives directly on top of the Transport layer.
is useful for troubleshooting network problems. 
the seven layers :


- layer 7: The Application Layer
interacts with data from the user

- layer 6: The Presentation Layer
makes the data presentable for applications to consume.

- layer 5: The Session Layer
responsible for opening and closing communication between the two devices.

- layer 4: The Transport Layer
responsible for end-to-end communication between the two devices. Also, is responsible for flow control and error control. 

- layer 3: The Network Layer
responsible for facilitating data transfer between two different networks. if the two devices using the same network then this layer will not use.

- layer 2: The Data Link Layer
facilitates data transfer between two devices on the SAME network. The data link layer takes packets from the network layer and breaks them into smaller pieces called frames.

- layer 1: The Physical Layer
like cables or switches.


## Internet Protocol Suite
is the conceptual model for the protocols used by the internet. It is often referred to as TCP/IP because the IP and TCP were the original protocols in the suite. used four layers model.

## TCP
Transmission Control Protocol, TCP and IP are the basic rules defining the Internet. the TCP used to orgnaize the data and ensure the security transmition between client and server. it is flexible and highly scalable, meaning new protocols can be introduced to it and it will accommodate them.