Socket.IO =>

Websocket / HTTP 

HTTP: CLIENT => SERVER
      CLIENT <= SERVER


IO => box with sockets 
socket => 1 client

Socket.IO: A JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers.
Socket: A virtual communication channel established between a client and a server.
Client: The web browser or application that connects to a server using Socket.IO.
Server: The application or server-side component that uses Socket.IO to communicate with clients.
Emit: The act of sending a message from either the client or the server to the other.
On: The method used to listen for messages on either the client or the server.
Broadcast: Sending a message from the server to all connected clients except the sender.
Room: A grouping of sockets that allows broadcasting messages to specific subsets of clients.
Namespace: A feature of Socket.IO that allows creating multiple communication channels on the same connection.
Acknowledgement: An optional feature that allows the receiver of a message to confirm its receipt.
Polling: A fallback mechanism used by Socket.IO to establish a connection in environments where WebSockets are not supported.
Long-polling: A variation of polling where the server holds the request open until new data is available.
WebSockets: A communication protocol that provides full-duplex communication channels over a single TCP connection. Used by Socket.IO for real-time communication when available.

npm install @mui/material @emotion/react @emotion/styled