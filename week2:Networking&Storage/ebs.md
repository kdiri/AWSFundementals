## Amazon EBS Notes

------

Amazon Elastic Block Store (Amazon EBS) provides persistent block storage volumes for use with Amazon EC2 instances in the AWS Cloud. Each Amazon EBS volume is automatically replicated inside an Availability Zone to protect you from component failure, which offers high availability and durability. Amazon EBS volumes offer the consistent and low-latency performance that you need to run your workloads.

Amazon EBS provides a range of options that allow you to optimize storage performance and cost for your workload. These options are divided into two major categories: SSD-backed storage for transactional workloads, such as databases and boot volumes (performance depends primarily on IOPS), and hard disk drive (HDD)-backed storage for throughput-intensive workloads, such as MapReduce and log processing (performance depends primarily on MB/s).

The Elastic Volume feature of Amazon EBS allows you to dynamically increase capacity, tune performance, and change the type of live volumes with no downtime or performance impact. This allows you to easily right-size your deployment and adapt to performance changes.

Pricing for Amazon EBS is based on the amount (volume) and type of Amazon EBS volume that you provision. For pricing information, see:[ https://aws.amazon.com/ebs/pricing/](https://aws.amazon.com/ebs/pricing/). Confirm that you are looking at cost in the correct Region.

Full details on Amazon EBS are available here: https://aws.amazon.com/ebs
