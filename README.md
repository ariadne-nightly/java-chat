# java-chat

This is a simple texting program in Java that allows two computers to text with each other using sockets. The program consists of two classes: `Client` and `Server`.

## How to Use

1. Copy the compiled `Client.class` and `Server.class` files to the two computers you want to use for texting.

2. Start the server on one of the computers by running the `Server` class. Make a note of the IP address of the computer running the server. You can find the IP address by running the `ipconfig` command on Windows or the `ifconfig` command on Linux or macOS.

3. Start the client on the other computer by running the `Client` class. When prompted for the server address, enter the IP address of the computer running the server.

4. Type messages in the client's console and press Enter to send them to the server. The server will print the messages it receives and send back an acknowledgment to the client. The client will print the acknowledgment.

5. To stop the program, press Ctrl-C in the console of either the client or the server.

Note that both computers must be connected to the same network, and any firewalls on the network must allow traffic on the port used by the program (in this example, port 5000). If you have trouble connecting the client to the server, try disabling firewalls or configuring them to allow traffic on port 5000.
