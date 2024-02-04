---
title: EFS
parent: Storage
layout: default
nav_order: EFS
---

# EFS
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

- AWS managed Network File System (NFS)
- **Pay per use** (no capacity provisioning)
- **Uses security group to control access to EFS**
- Lifecycle management feature to move files to **EFS-IA** after N days

## Performance Modes
- General Purpose
- Max I/O

## Throughput Modes
- Bursting
- Provisioned

## Storage Tiers
- Standard
- Infrequent Access
	- Cost to retrieve files, cheaper to store 

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/efs/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/elastic%20file%20system%20(efs)/)