# EBS
- **Bound to an AZ**
- Must provision capacity in advance (size in GB & throughput in IOPS
- To replicate an EBS volume across AZ or region, need to copy its snapshot
- EBS Multi-attach allows the same EBS volume to attach to multiple EC2 instances **in the same AZ**

## Types
- General Purpose SSD
	- gp3
	- gp2
- Provisioned IOPS SSD
	- io1
	- io2
	- **io2 Block Express**
		- Storage: 4 GiB - **64 TB**
		- Sub-millisecond latency
		- Max IOPS: 256,000
		- 1000 lOPS per GB
- Hard Disk Drives (HDD)
	- **Cannot be used as boot volume** for an EC2 instance
	- **Throughput Optimized HDD (st1)**
	- **Cold HDD (sc1)**

## Encryption
- Encrypted EBS volumes
	- **Data in-flight between the instance and the volume is encrypted**
	- All snapshots are encrypted
	- All volumes created from the snapshot are encrypted
- Unencrypted EBS volumes
	- Create an EBS snapshot of the volume
	- Copy the EBS snapshot and encrypt the new copy

## Snapshots
- **Data Lifecycle Manager (DLM)** can be used to automate the creation, retention, and deletion of snapshots of EBS volumes

## Reference
- [AWS Documentation](https://docs.aws.amazon.com/ebs/)
- [Abdur's Notes](https://notes.arkalim.org/notes/aws%20solutions%20architect%20associate/elastic%20block%20storage%20(ebs)/)
