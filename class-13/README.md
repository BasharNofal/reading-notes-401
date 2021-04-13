# Message Queues

## Review, Research, and Discussion

1. It's full duplex communication, it's very important when we are talking about real-time communication.
2. It uses http to set up the initial connection between the server and the client.
3. The server starts listening to that event by using `on()` method.
4. All clients start listening to that event.
5. Nothing will happen, it'll be the same as if it wasn't emitted.
6. By having handler for each emitted event.

### Terms 

**Socket:** it represents the port (endpoint) that's used for websocket service.

**Websocket:** it's technology that allows real-time full-duplex communication between client and server.

**Socket.io:** it's library that utilizes websocket technology.

**Client:** represents the receiver of a service (usually the user).

**Server:** the provider of the service itself.

**OSI Model:** stands for open system interconnection conventional layered model system, consists of seven layers that represents how data is sent between devices, and what each layer consists of.

**TCP Model:** stands for transmission control protocol, it's basically the same as OSI model but it's four layers model that are basically consists of the same data as the seven layers in the OSI model.

**TCP:** stands for transmission control protocol, it's transport layer protocol that is responsible for transmitting data and establishing tcp connection between two devices via three way handshake process.

**UDP:** stands for user datagram protocol, it's also transport layer protocol, but the difference between this protocol and tcp is udp doesn't establish connection via three way handshake so it's faster but less reliable than tcp.

**Packets:** we refer to the data sent after being encapsulated (adding data from each protocol in the layered models) with packets.

## Preview

**Rooms:** basically it's a channel where multiple sockets can join and can communicate with each other, where other sockets in other rooms can't communicate with the sockets outside their room.


