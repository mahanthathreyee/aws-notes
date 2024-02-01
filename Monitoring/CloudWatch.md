---
title: CloudWatch
parent: Monitoring and Logging
layout: default
nav_order: CloudWatch
---

# CloudWatch
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## EC2
* EC2 requires `CloudWatch agent` to be installed. (IAM must be enabled)
* Available metrics: 
	* CPU utilization
	* Network utilization
	* Disk performance
	* Disk reads/write
* **Custom metrics (not readily available)**
	* Memory utilization
	* Disk space and swap utilization
	* Page file utilization
* CW Unified Agent provides more metrics to monitor and has the option to send logs 
	* Requires to be configured and installed separately, not included
* If unified agent is not explicit installed then custom metrics have to be configured manually in cloudwatch for monitoring

## Dashboard
* Dashboards are global
* Can monitor metrics across regions and accounts
* Can be shared external even if they don't have AWS account (via Cognito or SSO etc)

## Logs
* Logs expiration is default `never` but can be configured

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/cloudwatch/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/cloudwatch/)