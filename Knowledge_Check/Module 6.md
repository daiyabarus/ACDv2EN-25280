AWS Module 4 Knowledge Check
Which option is the Amazon Web Services (AWS) customer responsible for under the AWS shared responsibility model? (Select TWO)

1. Security group configuration
2. Physical servers
3. Client-side data
4. Edge location infrastructure
5. Availability Zone security
1. Security group configuration
3. Client-side data

Which AWS Identity and Access Management (IAM) resource explicitly grants or denies permissions to a user or group of users?

1. IAM roles
2. IAM users
3. IAM groups
4. IAM policies
4. IAM policies

Which is the correct term for the process of verifying a user's identity as a developer?

1. Endorsement
2. Authentication
3. Confirmation
4. Authorization
2. Authentication

Which statements about IAM user authentication are true? (Select TWO)

1. AWS credentials to authenticate with any supported services must be provided.
2. A user name and password to authenticate to the console must be provided.
3. A .pem or .ppk file is used to authenticate programmatically to the AWS application programming interface (API).
4. It is a best practice to use the account root user credentials to authenticate programmatically by using the AWS Command Line Interface (AWS CLI).
5. Each AWS account can have only one administrator who manages other IAM users.
1. AWS credentials to authenticate with any supported services must be provided.
2. A user name and password to authenticate to the console must be provided.

Which suggestion is an Amazon Web Services (AWS) recommendation for securing AWS credentials for application that run on Amazon Elastic Compute Cloud (Amazon EC2) instances?

1. Embed AWS credentials in the software development kit (SDK) client code.
2. Store credentials in local AWS configuration files.
3. Create an AWS Identity and Access Management (IAM) role and attach it to the EC2 instance.
4. Create an AWS Identity and Access Management (IAM) user and attach it to the EC2 instance.
3. Create an AWS Identity and Access Management (IAM) role and attach it to the EC2 instance.

What is the format of AWS Identity and Access Management (IAM) polices that define the allowable API calls an entity can invoke?

1. YAML Ain't Markup Language (YAML)
2. Security Assertion Markup Language (SAML)
3. Comma-separated values (CSV)
4. Javascript Object Notation (JSON)
4. Javascript Object Notation (JSON)

An administrator created an AWS Identity and Access Management (IAM) groups called managers within an AWS account. A ____ policy is attached to the managers group. It allows managers to read from and write to an Amazon Simple Storage Service (Amazon S3) bucket in the same AWS account. What is this type of policy?

1. Identity-based
2. Resource-based
3. Cross-account access
4. AdministratorAccess managed
1. Identity-based

Which statement reflects best practices when granting permissions to users, groups, roles, and resources?

1. Create policies that allow broad access and then limit permissions as needed, based on usage.
2. Use the account root user for routine tasks that the administrator performs.
3. Create policies that follow the principle of least privilege.
4. Do not set policies for indivdual resources.
3. Create policies that follow the principle of least privilege.

What is the effect of the following policy statement?

{
"Effect": "Deny",
"Action":["dynamodb:", "s#:" ],
"NotResource": [ "arn:aws:dynamodb:region:account-number:table/pollynotes",
"arn:aws:s3:::polly-notes-web",
"arn:aws:s3:::polly-notes-mp3/*" ]
}

1. Denies actions on DynamoDB or Amazon S3 resources except for the resources that are listed in the NotResource element.
2. Denies actions on the DynamoDB table or S3 buckets that are listed in the NotResources element.
3. Denies the ability to write to the pollynotes DynamoDB table.
4. Denies the ability to read from the polly-notes-web S3 bucket.
1. Denies actions on DynamoDB or Amazon S3 resources except for the resources that are listed in the NotResource element.

Which statements are true about evaluation logic for AWS Identity and Access Management (IAM) policies? (Select TWO)

1. You cannot have deny and allow statements in the same policy.
2. An explicit allow overrides an explicit deny.
3. An explicit deny overrides and explicit allow.
4. By default, all requests are denied.
5. By default, all requests are allowed.
3. An explicit deny overrides and explicit allow.
#4. By default, all requests are denied.
