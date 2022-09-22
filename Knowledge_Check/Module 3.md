AWS Module 3 Knowledge Check

A student is learning about Amazon Simple Storage Service (Amazon S3). During an interview, a potential employers asks the student to explain how Amazon S3 can be used as a storage solution. Which option is a use case for Amazon S3?

1. Block-level storage
2. Hosting active databases
3. Shared files systems
4. Data lake
4. Data lake

A developer wants to store image files in a bucket that is called images-bucket, but receives the error BucketAlreadyExists. Which action must the developer take to resolve this error?

1. Bucket names are globally unique. If the requested bucket name is not available, the developer must rename the bucket.
2. Bucket names are unique to the Region that they are created in. If the requested bucket name is not available, the developer must create the images-bucket in a different Region.
3. The developer must contact AWS Support to request approval to use the same bucket name.
4. Bucket names go to the highest bidder. The developer must outbid the current bucket owner.
1. Bucket names are globally unique. If the requested bucket name is not available, the developer must rename the bucket.

A ______ organizes the Amazon Simple Storage Service (Amazon S3) namespace at the highest level.

1. Container
2. Group
3. Bucket
4. Region
3. Bucket

A developer is using Amazon Simple Storage Service (Amazon S3) to host a static website in a bucket called frank-martha-cafe. This bucket is in the us-east-1 Region. Which URL is the virtual-hosted-style URL for their website?

1. https://s3-website-us-east-1.amazonaws.com/frank-martha-cafe
2. https://frank-martha-cafe.s3-us-east-1.amazonaws.com
3. https://www.frank-martha-cafe.s3-website-us-east-1.amazonaws.com
4. https://frank-martha-cafe.s3-website-us-east-1.amazonaws.com
4. https://frank-martha-cafe.s3-website-us-east-1.amazonaws.com

True or False: After versioning is enabled on an Amazon Simple Storage Service (Amazon S3) bucket, it can be disabled.

1. True
2. False
2. False

What is the largest size of an object that a user can upload to Amazon Simple Storage Service (Amazon S3) in a single PUT operation?

1. 1 GB
2. 5 GB
3. 100 MB
4. 5 TB
2. 5 GB

A developer uses an Amazon Simple Storage Service (Amazon S3) bucket. They want to allow a certain AWS Identity and Access Management (IAM) user to perform any S3 operation on the bucket and its objects. They also want to follow AWS recommendations for granting permissions. Which mechanism should the developer apply to the bucket?

1. Bucket access control list (ACL)
2. IAM policy
3. Cross-Origin resource Sharing (CORS)
4. Bucket policy
4. Bucket policy

A developer wants to allow a user to download objects directly from an Amazon Simple Storage Service (Amazon S3) bucket without needing AWS security credentials or permissions. What can the developer share with the user to grant them time-limited access to the objects.

1. A presigned URL
2. A temporary token
3. The bucket endpoint URL
4. Their AWS account root user credentials
# 3. The bucket endpoint URL

Which method can be used to encrypt Amazon Simple Storage Service (Amazon S3) objects in transit?

1. Server-Side Encryption with Customer-Provided Keys (SSE-C)
2. Secure Sockets Layer/Transport Layer Security (SSL/TLS)
3. Server-Side Encryption with Amazon S3-Managed Keys (SSE-S3)
4. Server-Side Encryption with AWS KMS-Managed Keys (SSE-KMS)
2. Secure Sockets Layer/Transport Layer Security (SSL/TLS)

A developer hosts a static website in an Amazon Simple Storage Service (Amazon S3) bucket. The website references image objects in another S3 bucket. However, these images do no display on the website. What could be the problem?

1. Cross-Origin Resource Sharing (CORS) has not been enabled on the bucket where the assets are stored
2. Cross-region Replication (CRR) has not been enabled on the bucket where the assets are stored.
3. Amazon S3 does not support object sharing between buckets.
4. The security group of the S3 bucket does not include an inbound rule to allow HTTP traffic on port 80.
1. Cross-Origin Resource Sharing (CORS) has not been enabled on the bucket where the assets are stored
