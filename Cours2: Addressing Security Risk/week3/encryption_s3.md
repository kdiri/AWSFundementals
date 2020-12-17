## Amazon S3 Default Encryption for S3 Buckets

------

Amazon S3 default encryption provides a way to set the default encryption behavior for an S3 bucket. You can set default encryption on a bucket so that all objects are encrypted when they are stored in the bucket. The objects are encrypted using server-side encryption with either Amazon S3-managed keys (SSE-S3) or AWS KMS-managed keys (SSE-KMS).

When you use server-side encryption, Amazon S3 encrypts an object before saving it to disk in its data centers and decrypts it when you download the objects. More details on using Encryption with Amazon S3 can be found at: https://docs.aws.amazon.com/AmazonS3/latest/dev/bucket-encryption.html

### Amazon Macie 

Amazon Macie is a security service that uses machine learning to automatically discover, classify, and protect sensitive data in AWS. Amazon Macie recognizes sensitive data such as personally identifiable information (PII) or intellectual property, and provides you with dashboards and alerts that give visibility into how this data is being accessed or moved. The fully managed service continuously monitors data access activity for anomalies, and generates detailed alerts when it detects risk of unauthorized access or inadvertent data leaks. Currently, Amazon Macie is available to protect data stored in Amazon S3. More information about Amazon Macie is available at: https://aws.amazon.com/macie/
