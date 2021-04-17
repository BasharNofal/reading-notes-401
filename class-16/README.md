# AWS: Cloud Servers 

## Review, Research, and Discussion 

1. * Standard queue preserves the ordering of the data but there is possibility that a some data being      delivered out of order, whereas in FIFO queue the order is preserved.
   * FIFO queue has worst performance due to the delivery order.
   * Standard queue guarantees message delivery at least once, whereas FIFO queue guarantees only once.

2. The receiver sends a TCP acknowledgement message when the delivery is done and all packets agreed upon were delivered.

3. Observer pattern.

4. There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.

### Terms

**Server:** a device that manages and provide services to the network.

**Pub/Sub:** stands for publish/subscribe, it's a real time, flexible, and reliable messaging service to publish and subscribe to asynchronous events.

**WRRC:** stands for web response request cycle, it's a graph that represent outgoing and incoming requests and responses from each device in a certain application.

<hr>

## Preview

**Virtual Machines:** it's a machine that runs simultaneously on another device by sharing its resources with the original device. This service can be provided by multiple companies where you can setup your machine (operating system, memory, processor, .... etc) and you can run it as if it was a device between your hands.

**AMAZON EC2:** stands for elastic computing cloud, it's web services provided by amazon where you can setup your instances that suites your application and run them as normal machines.  



