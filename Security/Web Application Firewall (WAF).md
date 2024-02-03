---
title: AWS WAF
parent: Security
layout: default
nav_order: AWS WAF
---

# Web Application Firewall (WAF)
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
* Protects against layer 7 attacks (SQL injection and XSS)
* Can be deployed only on:
	* ALB (not ELB or NLB)
	* API Gateway
	* CloudFront
* Provide ACL option to filter requests
	* IP Addresses
	* Geo match
	* Rate based rules (DDoS)

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/shield/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/web%20application%20firewall%20(waf)/)