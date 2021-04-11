# Socket.io

## Review, Research, and Discussion

1. 
   * Dividing data before sending it will be less likely to loose data and less likely to get distorted.
   * It will utilize less resources since it will use less bandwidth.
2. Because it doesn't initiate the connection with permission from the receiver.
3. Yes they can as long as the connection was established with different clients.
4. No they can't because clients ports are only associated with one service where they can only receive data from one transmitter.
5. Yes they can.

### Terms

**Observer Pattern:** software design pattern where an object notifies its dependencies (Observers) in case a certain change occurs, it's usually used when having one to many relationship between objects

**Listener:** function listens to a certain event to occur.

**Event Handler:** a callback function that runs when an event occurs.

**Event Driven Programming:** programming design in which event listeners are used.

**Event Loop:** it's the mechanism that allows node.js to execute functions without blocking other functions to be executed since it doesn't wait for the result for each function.

**Event Queue:** it's where events are held before executing them.

**Call Stack:** it's where operations of the code are held to be executed in sequence by the interpreter.

**Emit/Raise/Trigger:** emit is the initiation of events, and raise them to the event queue once they are triggered.

**Database:** it's where data are stored in an organized way so it will be easy to restore them.

## Preview

**OSI:** stands for Open Systems Interconnection, which is conventional layered model that represents how data are being sent between devices. It consists of seven layers.

**TCP handshake:** it's the process of establishing TCP connection between devices where they agree upon the sequence number and how many segments will be sent.

**Web Socket:** protocol that provide us with the ability of establishing duplex TCP connection, it's used when you need to send a lot of data in real time then negotiating a tcp connection every time will make it slower. 

Web socket provides the Connection over TCP, while Socket.io is a library to abstract the WebSocket connections. WebSocket doesn't have fallback options, while Socket.io supports fallback. WebSocket is the technology, while Socket.io is a library for WebSockets.
