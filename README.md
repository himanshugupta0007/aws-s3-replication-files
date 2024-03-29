# AWS S3 - Replication Configuration

### What is AWS S3 Replication?

AWS S3 provides the fully managed feature to automatically replicate the newly uploaded objects between your buckets to help you reduce cost, protect your data, and meet your compliance needs.

### AWS offers two types of replication:-

- AWS Same Region Replication (SRR) - replicates objects between Amazon S3 source and destination buckets in the same AWS region
- AWS Cross-Region Replication (CRR) - replicates objects between Amazon S3 source and destination buckets in the different AWS region
- AWS Cross Account Replication - replicates objects between Amazon different AWS Account in same or different regions

### What is AWS S3 Same Region Replication (SRR)?

AWS S3 allows replicating the newly uploaded objects to S3 destination buckets asynchronously, automatically present in the same region as the source bucket but in a different Availability Zone.

Users can configure the replication rule so the rule can identify the objects to replicate using prefix, tag, or bucket through AWS CLI, Management Console, and AWS SDK.

Blog Post on how to configure Replication Rule for AWS S3 Same Region - [Link](https://programmersblock.hashnode.dev/aws-s3-same-region-replication)

### What is AWS S3 Cross-Region Replication (CRR)?
Amazon S3 allows cross region replication of the newly uploaded objects to S3 destination buckets asynchronously and automatically across different AWS Regions.

Users can configure the replication rule so the rule can identify the objects to replicate using prefix, tag, or bucket through AWS CLI, Management Console, and AWS SDK.

Blog Post on how to configure Replication Rule for AWS S3 Cross Region - [Link](https://programmersblock.hashnode.dev/amazon-s3-cross-region-replication)


### What is AWS S3 Cross Account Replication (CRR)?
AWS S3 Cross Account replication refers to copying S3 objects between buckets in different AWS Accounts. These AWS Accounts might be owned by the same organization or by other individuals.

Configuring AWS S3 Cross Account replication is similar to S3 Same Region replication and S3 Cross Region replication, with a difference in providing the bucket policy to the destination bucket allowing the source bucket owner to replicate objects to the destination bucket.

Blog Post on how to configure Replication Rule for AWS S3 Cross Region - [Link](https://programmerblock.com/how-to-configure-s3-cross-account-replication/)
