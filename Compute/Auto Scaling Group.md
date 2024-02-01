---
title: Auto Scaling Group
parent: Compute
layout: default
nav_order: Auto Scaling Group
---

# Auto Scaling Group
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

- A instance can only be part one ASG at a time
* Scaling Policies
	* Scheduled
	* Simple (CloudWatch alarm trigger)
	* Step (Incremental with CloudWatch alarm)
	* Target Tracking (ASG maintains the CloudWatch alarm)
	* Predictive (ML analysis to scale automatically)

## Scaling Cooldown
* After scaling activity, ASG goes into `300 sec` cooldown period before next scaling action is performed

## Instance Termination
* In case of unhealthy instance, it deletes the instances as a scale down and then scales up again. 
	* By default it can take `600 seconds` (`300 sec` for scale down and `300 sec for scale up`) for the entire replacement activity from ASGs perspective

### Termination Policy
* Select the AZ with the most number of instances
	- Delete the instance with the oldest launch configuration
	- Delete the instance which is closest to the next billing hour
	- Choose at random

## Reference:
* [AWS Documentation](https://docs.aws.amazon.com/autoscaling/)
* [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/auto%20scaling%20group%20(asg)/)