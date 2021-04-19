# AWS: API, Dynamo and Lambda

## Review, Research, and Discussion

1. * Standard queue preserves the ordering of the data but there is possibility that a some data being delivered out of order, whereas in FIFO queue the order is preserved.
   * FIFO queue has worst performance due to the delivery order.
   * Standard queue guarantees message delivery at least once, whereas FIFO queue guarantees only once.

2. The receiver sends a TCP acknowledgement message when the delivery is done and all packets agreed upon were delivered.

3. Observer pattern.

4. There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.

### Terms

**Serverless Functions:** function that you can run without configuring, managing, and maintaining a server.

**Cloud Storage:** storage service where you can store your data in a remote databases by the service provider.

**CDN:** stands for Content Delivery Network, it's geographically distributed group of servers that work together to provide fast delivery of internet content.

## Preview

**AWS API Gateway:** Amazon computing service where you can configure routes for your api server that's hosted by Amazon, you add your routes then they will provide you with domain so that you can access it.

**AWS DynamoDB:** noSQL database service provided by Amazon.

**Dynamoose:** it's a package that allows you to interact with dynamodb using javascript.