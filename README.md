# aws-kinesis-reference-streaming
Collection of references for AWS Kinesis to stream data

### Kinesis Services
* Kinesis Streams.  https://aws.amazon.com/kinesis/data-streams/
* Kinesis Analytics.  https://aws.amazon.com/kinesis/data-analytics/
* Kinesis Firehose.  https://aws.amazon.com/kinesis/data-firehose/
* Managed Streaming for Apache Kafka.  https://aws.amazon.com/msk/

### References:
* Whitepaper streaming data solutions on AWS with Amazon Kinesis.  https://d0.awsstatic.com/whitepapers/whitepaper-streaming-data-solutions-on-aws-with-amazon-kinesis.pdf
* Documentation Key KPL Concepts.  https://docs.aws.amazon.com/streams/latest/dev/kinesis-kpl-concepts.html#kinesis-kpl-concepts-aggretation
* Documentation Configuring the Kinesis Producer Library.  https://docs.aws.amazon.com/streams/latest/dev/kinesis-kpl-config.html
* Documentation KPL Retries and Rate Limiting.  https://docs.aws.amazon.com/streams/latest/dev/kinesis-producer-adv-retries-rate-limiting.html. 
  * The PutRecords operation sends requests to your stream that occasionally exhibit full or partial failures. Records that fail are automatically added back to the KPL buffer. 
* Announcement Lambda supports MSK as an event source.  https://aws.amazon.com/about-aws/whats-new/2020/08/aws-lambda-now-supports-amazon-managed-streaming-for-apache-kafka-as-an-event-source/
* Documentation Real-time processing of cloudwatch logs subscriptions to Kinesis.  https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/Subscriptions.html
