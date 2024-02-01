---
title: API Gateway
parent: Serverless
layout: default
nav_order: API Gateway
---

# API Gateway
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

* Invoke lambda using REST APIs
* Can throttle requests
* Cache responses

## Endpoints
* Edge Optimized 
	* API Gateway in one region and accessed globally via CloudFront Edge
* Regional
	* For regional access
* Private
	* Can be access only inside the VPC 

## Authentication
* Cognito user pools for authentication and giving access to users

## Canary Deployment
* Deployment strategy for API version upgrade. Allows to direct portion of traffic to new version and gradually deprecate the old version. 
* Cheaper than blue/green deployment in terms of resources need for deployment

# Reference:
* [AWS Documentation](https://docs.aws.amazon.com/apigateway/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/api%20gateway/)