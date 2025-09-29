

The client initiates a connection with server by sending a **TCP** **SYN** packet.


The first **SYN** message contains a random number (**Initial Sequence Number**), unique to each new connection.


### Step 1
To begin, enter a random four digit number here that will be used as the **ISN** to initiate communication.


The server responds with a **SYN-ACK** packet.


**SYN** indicates the random sequence number that the server will be using.

**ACK** is an acknowledgement to the client's **SYN** and is calculated as clientSYN + 1.

### Step 2
Enter a random number that will be **SYN** for the server.

Now, data packet transfer can begin. Try transferring a packet from the client to the server.

### Step 3
Enter a random string to send to the server and observe the transfer and response.

