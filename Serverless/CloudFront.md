---
title: CloudFront
parent: Serverless
layout: default
nav_order: CloudFront
---

# CloudFront
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
* Global CDN
* Capable of configuring Geo restriction
* Deploy WAF for IP blocking

## Signed URL / Cookies
* Allows for making content private and restrict access
* Signed URL = access to individual files
- Signed Cookies = access to multiple files

## Pricing
- Price Class All: all regions (best performance)
- Price Class 200: most regions (excludes the most expensive regions)
- Price Class 100: only the least expensive regions

## Origin Groups
- Allows for failover to secondary
- The secondary can be in a different region

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/cloudfront/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/cloudfront/)