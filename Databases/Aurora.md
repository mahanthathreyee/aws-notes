---
title: Aurora
parent: Databases
layout: default
nav_order: Aurora
---

# Aurora
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

* Supports only MySQL and PostgresSQL
* Maintains 6 copies of data across 3 AZs
* Maintains a master and and data is replicated to read nodes
	* In case multi master enabled, all nodes can read and write data and the data is replicated all other nodes
		* Multi master allows for having multiple DB connections to handle failover
* You can invoke lambda function using native functions or stored procedures

## Endpoint
* Specific Writer and Reader Endpoints for accessing the database
* Custom Endpoint
	* To allow only a subset of replicas to be accessed (as read or read-write) based on a criteria

## Aurora Severless
* Good for unpredictable load
* Scaling handled by AWS
* Pay per second

## Aurora Global Database
* DB is replicated across regions
* 1 region is designated master and upto 5 secondary regions read nodes
	* Upto 16 replicas per region
* Reduce latency and provides high availability

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/aurora/)