# Dynamo DB
* Maximum size of item is `400 KB`
* Primary key can be single or pair of fields
	* Pair of field is defined as (partition key and sort key)
* Allows for TTL

## DynamoDB Accelerator (DAX)
* An add-on to cache queries and reduce read congestions
* Cache has default **TTL** of `4 mins`

## DynamoDB Streams
* Notification when there are changes in items
* Destinations: Kinesis Data Streams, AWS Lambda, KCL
* Data retention: `24 hrs`

## Global Tables
* Multi-region access
* Replication handled by AWS across regions
	* Active-Active Replication
* **DynamoDB Streams must be enabled**