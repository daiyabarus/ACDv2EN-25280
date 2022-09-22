AWS Module 5 Knowledge Check
Which statement best describes Amazon DynamoDB?

1. An in-memory data store that can boost the performance of databases
2. A graph database engine that is optimized for storing billions of relationships
3. A relational database that is built for the cloud and is compatible with the MySQL and PostgreSQL
4. A key-value and document database that scales horizontally and works well for internet-scale applications
4. A key-value and document database that scales horizontally and works well for internet-scale applications

Which component is part of the Amazon DynamoDB table?

1. Predefined schema
2. SQL-based queries
3. Attributes
4. Columns
3. Attributes

An Amazon DynamoDB table called SensorReadings captures sensor readings. These readings include a sensor ID attribute that acts as the partition key, and a timestamp attribute that is the sort key. Which statement is true?

1. The sensor ID together with the timestamp represent a simple primary key.
2. It is impossible for two items in the SensorReadings table to have the same partition key.
3. It is impossible for two items in the SensorReadings table to have the same sort key.
4. It is impossible for two items in the SensorReadings table to have the same primary key.
4. It is impossible for two items in the SensorReadings table to have the same primary key.

Which statement about Amazon DynamoDB partitions is true?

1. DynamoDB stores data in partitions and chooses the partition based on the range attribute.
2. If a table has a simple primary key (partition key only), DynamoDB stores and retrieves each item based on its hash attribute.
3. If a table has a composite primary key, DynamoDB will sort the items based on the sort key before selecting the partition for the item.
4. A developer writes a hash function to tell DynamoDB how to partition the items.
2. If a table has a simple primary key (partition key only), DynamoDB stores and retrieves each item based on its hash attribute.

Suppose that a developer has a restaurants database table that can be queried by name (the partition key), or by name and location (the sort key). What should the developer do if they also want to query by the type of cuisine and average customer rating?

1. Set up a local secondary index on cuisine and customer rating.
2. Set up a global secondary index on cuisine and customer rating.
3. Change the primary key on the restaurant table to be a complex primary key based on cuisine and customer rating.
4. Perform a query that uses the cuisine and average customer rating attributes.
#3. Change the primary key on the restaurant table to be a complex primary key based on cuisine and customer rating.

A video game developer who sues Amazon DynamoDB wants to ensure that players' profiles are updated correctly when they make in-game purchases. This process requires multiple updates as part of the single user action. What is the best choice tow rite this developer's application to manage these complex, all-or-nothing changes?

1. Add an Amazon DynamoDB Accelerator (DAX) cluster.
2. Implement global tables.
3. Create application code to check that all parts of the transaction were written successfully, and then roll back the update if any part failed.
4. Use DynamoDB transactions.
4. Use DynamoDB transactions.

Which scenarios are example use cases for Amazon DynamoDB Streams? (Select TWO)

1. An application that requires the fastest possible response time for reads to support real-time bidding
2. An application that requires repeated reads against a large set of regional weather data to perform a long-running analysis
3. An application that automatically sends notifications to the mobile devices of all friends in a group when one friend uploads a new picture
4. An application that must monitor changes to a DynamoDB table and take action on specific changes when a value reaches a certain threshold
5. An application that requires an in-memory data store
3. An application that automatically sends notifications to the mobile devices of all friends in a group when one friend uploads a new picture
4. An application that must monitor changes to a DynamoDB table and take action on specific changes when a value reaches a certain threshold

Which statement about global tables is true?

1. Global tables provide a managed solution for replicating tables within a single AWS Region.
2. Global tables use Amazon Simple Storage Service (Amazon S3) to propagate changed between replicas.
3. When a global table is created, Amazon DynamoDB performs all necessary tasks to create identical tables and propagate ongoing data changes to specified Regions.
4. With a global table, Amazon DynamoDB supports partial replication of some of the items in a table.
3. When a global table is created, Amazon DynamoDB performs all necessary tasks to create identical tables and propagate ongoing data changes to specified Regions.

How far in days can an Amazon DynamoDB table be restored by using point-in-time recovery?

1. The last week
2. The last 10 days
3. The last 35 days
4. The last calendar month
3. The last 35 days

Which statement describes Amazon DynamoDB application programming interface (API) control operations that can invoked by an application?

1. Create and manage DynamoDB tables.
2. Create, read, update, and delete data in a table.
3. Get and write batches of items in a DynamoDB table.
4. Make coordinated, all-or-nothing changes to multiple items both within and across tables.
1. Create and manage DynamoDB tables.