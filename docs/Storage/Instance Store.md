---
title: Instance Store
parent: Storage
layout: default
nav_order: Instance Store
---

# Instance Store
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

- **Hardware storage directly attached to EC2 instance** (cannot be detached and attached to another instance)
- Good for buffer / cache / scratch data / temporary content
- AMI created from an instance does not have its instance store volume preserved

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/instance%20store/)