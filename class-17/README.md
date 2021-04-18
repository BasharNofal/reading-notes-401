# AWS: S3 and Lambda

## Review, Research, and Discussion

1. * Standard queue preserves the ordering of the data but there is possibility that a some data being delivered out of order, whereas in FIFO queue the order is preserved.
   * FIFO queue has worst performance due to the delivery order.
   * Standard queue guarantees message delivery at least once, whereas FIFO queue guarantees only once.

2. The receiver sends a TCP acknowledgement message when the delivery is done and all packets agreed upon were delivered.

3. Observer pattern.

4. There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.

### Terms

**Server Instances:** SQL server instance is a SQL server that has its own copy of the server files, databases and security credentials.

**Containers:** a container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

**Cloud Services:** computing services hosted by service providers on their machines.

**Cloud Architecture:** it's the components that powers a cloud service and the relationships between these components. By components I mean the databases, software, hardware of the server ... etc.

**AWS:** refers to Amazon Web Services, it's computing services provided by amazon.

**EC2/Beanstalk vs Heroku:** EC2/Beanstalk is considered as infrastructure as a service (IaaS), whereas Heroku is (PaaS), in PaaS you have less things to configure, whereas IaaS you have to configure your virtual machine from top to bottom (CPU, RAM, storage, OS, security configurations ... etc).

<hr>

## Preview

**AWS S3:** refers to Amazon Simple Storage Service, it's an object storage service that offers high scalability, security, data availability, and performance.

**AWS Lambda:** serverless computing service that allows you to run your code without managing or provisioning your machine, with Lambda you can run your backend code with zero administration.