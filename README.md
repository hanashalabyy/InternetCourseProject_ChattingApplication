In Milestone 0 , You are required to build a chatting application designed over a
network composed of one client and a server. The chatting application should feature
the following:
1. The client chats with the server at any time.
2. The server responds with the same message sent by the corresponding client in CAPITALIZED format.
3. The connection between any client and server stays open until the client sends to the server
a message contains CLOSE SOCKET then the connection between the server and the client
closes.
4. The chatting connections are TCP based.
5. Server WILL NEVER TERMINATE * For Example: “When Client 1 sends any
message to the server then terminates, the server should continue running (should stay available)
so when you re-run Client class you should succeed connecting to the server again as client 2
(MileStone 1)”
In Milestone 1 , You are required to extend your chatting application designed over a 
network to be composed of N clients and a single server. The server should communicate 
with N clients concurrently. The chatting application should feature the following:
1. The server should communicate with the N clients concurrently (using threading). 
Note: you will find a pdf file on cms for the concept of threading
2. The server should saves the client information such as the connection socket, 
outputstream, etc. (use any data structure such as linkedlist, array, .etc)
3. Any client chats with the server at any time.
4. The server responds with the same message sent by the corsponding client in 
CAPITALIZED format.
5. The connection between any client and server stays open until the client sends to 
the server a message contatins CLOSE SOCKET then the connection between the 
server and the client closes.
In Milestone 2, You should initiate the communication between the client and the server;
the client will be installed on the ESP8266 Wi-Fi module.
• We have here two ESP8266 modules (clients) which will send the readings of
the sensors to the python server implemented in previous milestones.
• The clients should be able to send data (assume a number or a string) to the server.
• The clients should periodically send data to the server.
• The server should be able to communicate to multiple clients in parallel (as in milestone 1).
In Milestone 3, Our main objective is Building a complete IoT system. We are
going to connect our ESP module to an IoT platform. We are going to use ThingsBoard IoT 
platform to replace your Python Server.
