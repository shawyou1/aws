# SNS (Amazon Simple Notification Service)
### Fully managed publisher/ subscriber messaging for microservices, distributed systems, and serverless applications
you can receive e-mail notification for any event occurs in the aws. This service is configureable.
Amazon SNS provides topics for high-throughput, push-based, many-to-many messaging.
SNS uses the publish/subscribe model for push delivery of messages.Recipients subscribe to one or more 'topics' within SNS. 


# EBS Snapshot (elastic block store)
You can back up the data on your Amazon EBS volumes to Amazon S3 by taking point-in-time snapshots. Snapshots are incremental backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved.
Each snapshot contains all of the information that is needed to restore your data (from the moment when the snapshot was taken) to a new EBS volume.
Multi-volume snapshots allow you to take exact point-in-time, data coordinated, and crash-consistent snapshots across multiple EBS volumes attached to an EC2 instance.
You can track the status of your EBS snapshots through CloudWatch Events.


# Versoning
Versioning is a means of keeping multiple variants of an object in the same bucket. 
When you enable versioning for a bucket, if Amazon S3 receives multiple write requests for the same object simultaneously, it stores all of the objects.
If you enable versioning for a bucket, Amazon S3 automatically generates a unique version ID for the object being stored. In one bucket, for example, you can have two objects with the same key, but different version IDs, such as photo.gif (version 111111) and photo.gif (version 121212).



