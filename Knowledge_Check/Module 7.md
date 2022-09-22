AWS Module 7 Knowledge Check
Which statement describes a characteristic of AWS Lambda?

1. Lambda runs code only when it is activated by an event and uses only the compute resources that are needed.
2. A developer's methods and configuration options for ensuring high availability with Lambda are similar to their approach with Amazon Elastic Compute Cloud (Amazon EC2)
3. Lambda function run in on-demand, temporary environments, and the developer controls when new environments are created or shut down.
4. A developer must write Lambda functions that use one of the runtimes that the Lambda service provides.
1. Lambda runs code only when it is activated by an event and uses only the compute resources that are needed.
Which constraint cannot be modified?

1. Function timeout
2. Reserved concurrency
3. Burst quota
4. Regional quota
3. Burst quota
Which option best describes how Amazon API Gateway invokes AWS Lambda?

1. API Gateway directly invokes a function with a synchronous invocation.
2. Lambda processes API Gateway requests asynchronously and retires each request up to two times.
3. Lambda uses an event source mapping and polls API Gateway for requests
4. API Gateway directly invokes a function and retires the request until it succeeds or expires.
1. API Gateway directly invokes a function with a synchronous invocation.
Which actions require permissions that are defined in the AWS Lambda execution role? (Select TWO)

1. A Lambda function writes to an Amazon DynamoDB table.
2. An object that is written to an Amazon Simple Storage Service (Amazon S3) bucket initiates invocation of a Lambda function.
3. Lambda polls an Amazon Simple Queue Service (Amazon SQS) queue for messages that initiate invocation of a Lambda function.
4. An Amazon API Gateway GET route initiates invocation of a Lambda function.
5. A message that is posted to an Amazon Simple Notification Service (Amazon SNS) topic initiates invocation of Lambda function.
1. A Lambda function writes to an Amazon DynamoDB table.
3. Lambda polls an Amazon Simple Queue Service (Amazon SQS) queue for messages that initiate invocation of a Lambda function.
Which statement about the function handler in an AWS Lambda function is true?

1. The function handler is the entry point that Lambda calls to start running the Lambda function.
2. The function handler method might take an event object or context object.
3. The event object provides information about the event that invoked the Lambda function. It must be predefined object that an AWS services generates.
4. The context object provides runtime information, and the developer must create a context object that matches the runtime that was selected for the function.
1. The function handler is the entry point that Lambda calls to start running the Lambda function.
Which issue might be addressed by adding provisioned concurrency to an AWS Lambda function?

1. Another Lambda function runs in the same account and Region. It sometimes spikes and consumes all available concurrency, causing the function to fail.
2. An application that uses the Lambda function responds slowly for the first few users who sign in each day. Lambda metrics show higher latency for those initial requests.
3. A legacy backend system fails intermittently when the developer connects to it. To avoid extra costs, they want to reduce the function's wait time when the backend fails.
4. The developer wants more visibility into transactions that use the Lambda function to identify bottlenecks.
2. An application that uses the Lambda function responds slowly for the first few users who sign in each day. Lambda metrics show higher latency for those initial requests.
Which AWS Lambda configuration setting might be a developer use to manage function errors when configuring an Amazon Simple Notification Service (Amazon SNS) topic as the event source for a Lambda function? (Select TWO)

1. State machines
2. File Systems
3. Destinations
4. Virtual private cloud
5. Asynchronous invocations
3. Destinations
5. Asynchronous invocations
A zipped deployment package including code and custom libraries is 75MB in size. Which AWS Lambda deployment option should be used?

1. Copy the code into the Lambda console editor to create and deploy the function.
2. Upload a .zip file from an integrated development environment (IDE) to load the deployment package directly into the Lambda console.
3. Upload the deployment package to an Amazon Simple Storage Service (Amazon S3) bucket, and specify the bucket name and object key on the Lambda console.
4. Upload the deployment package to an Amazon Elastic Block Store (Amazon EBS) volume, and us the File Systems configuration to reference it.
3. Upload the deployment package to an Amazon Simple Storage Service (Amazon S3) bucket, and specify the bucket name and object key on the Lambda console.
A function's Amazon Resource Name (ARN) is as follows:

arn:aws:lambda:aws-region:acct-id:function:helloworld:PROD

Which statement about this function is correct, based on its ARN?

1. This ARN will invoke the immutable PROD version of the function.
2. This ARN will invoke the version of the function that is currently associated with the PROD alias.
3. This ARN will invoke the function and include the AWS Lambda layer that is named PROD
4. This ARN will deploy the helloworld function into the PROD account.
2. This ARN will invoke the version of the function that is currently associated with the PROD alias.
Users of a serverless application have reported errors that occur when they try to retrieve order information. Assuming that AWS X-Ray is enabled, what is the first step the developer might take in X-Ray to start troubleshooting the reported issues quickly?

1. Drill down into the most recent traces to look for errors.
2. Search for metadata that is related to the users who are reporting issues.
3. Add annotations that the developer can sue to start grouping and filtering traces.
4. Use the service map to visually locate errors across the application.
4. Use the service map to visually locate errors across the application.