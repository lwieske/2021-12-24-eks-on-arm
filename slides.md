---
marp: true
---

<!-- _class: invert -->

# EKS on ARM

* Amazon Elastic Kubernetes Service (EKS) customers can now run production
  workloads using Arm-based instances including the recently launched Amazon EC2
  M6g, C6g, and R6g instances powered by AWS Graviton2 processors.  

---

## AWS Graviton

* AWS Graviton processors are custom built by Amazon Web Services using 64-bit
  Arm Neoverse cores to deliver the best price performance for your cloud
  workloads running in Amazon EC2. The new **general purpose (M6g)**,
  **compute-optimized (C6g)**, and **memory-optimized (R6g)** instances deliver
  up to 40% better price/performance over comparable current generation
  x86-based instances for scale-out and Arm-based applications such as web
  servers, containerized microservices, caching fleets, and distributed data
  stores that are supported by the extensive Arm ecosystem.  

---

## EKS ARM Support

* Arm-based instances were previously available on EKS as part of a public
  preview. With general availability, you can mix x86 and Arm based EC2
  instances within a cluster, and easily evaluate Arm-based application in
  existing environments. 

* EC2 Arm-based instances are supported on new and existing clusters running
  Kubernetes version 1.15 and above, and can be deployed using EKS managed node
  groups, eksctl, CloudFormation, or the AWS CLI. To get started, visit the
  Amazon EKS documentation. To learn more about Arm-based instances and AWS
  Graviton, check out the Amazon EC2 documentation.

---

## AWS Graviton Processors

* AWS Graviton processors are designed by AWS to deliver the best price
  performance for your cloud workloads running in Amazon EC2.

---

## AWS Graviton 2

* AWS Graviton2 processors deliver a major leap in performance and capabilities
  over first-generation AWS Graviton processors.   Graviton2-based instances
  support a wide range of general purpose, burstable, compute-optimized,
  memory-optimized, storage-optimized, and accelerated computing workloads
  including application servers, microservices, high-performance computing
  (HPC), CPU-based machine learning (ML) inference, video encoding, electronic
  design automation, gaming, open-source databases, and in-memory caches. Many
  AWS services, including Amazon Aurora, Amazon ElastiCache, Amazon EMR, AWS
  Lambda, and AWS Fargate, also support Graviton2-based instances for a fully
  managed experience with significant price performance benefits.

---

## AWS Graviton 3

* AWS Graviton3 processors are the latest in the AWS Graviton processor family.
  They provide up to 25% better compute performance, up to 2x higher
  floating-point performance, and up to 2x faster cryptographic workload
  performance compared to AWS Graviton2 processors. AWS Graviton3 processors
  deliver up to 3x better performance compared to AWS Graviton2 processors for
  ML workloads, including support for bfloat16. They also support DDR5 memory
  that provides 50% more memory bandwidth compared to DDR4.

---

## Best Price Performance For A Broad Range Of Workloads

* AWS Graviton2-based general purpose burstable (T4g), general purpose (M6g),
  compute-optimized (C6g), and memory-optimized (R6g, X2gd) EC2 instances and
  their variants with NVMe-based SSD storage deliver up to 40% better price
  performance over comparable current generation x86-based instances1 for a
  broad spectrum of workloads such as application servers, microservices, video
  encoding, high-performance computing, electronic design automation,
  compression, gaming, open-source databases, in-memory caches, and CPU-based
  machine learning inference.

---

## Extensive Software Support

* AWS Graviton processors are supported by many Linux operating systems
  including Amazon Linux 2, Red Hat Enterprise Linux, SUSE, and Ubuntu. Many
  popular applications and services for security, monitoring and management,
  containers, and continuous integration and delivery (CI/CD) from AWS and
  software partners also support AWS Graviton-based instances. The AWS Graviton
  Ready program provides customers with certified solutions from partner
  software vendors that can be used on AWS Graviton-based instances.

---

## Enhanced Security For Cloud Applications

* AWS Graviton processors feature key capabilities that enable you to run cloud
  native applications securely, and at scale. AWS Graviton3 processors feature
  always-on memory encryption, dedicated caches for every vCPU, and support for
  pointer authentication. EC2 instances powered by AWS Graviton processors are
  built on the AWS Nitro System that features the AWS Nitro security chip with
  dedicated hardware and software for security functions, and support for
  encrypted Amazon Elastic Block Store (EBS) volumes by default.

---

## Available With Managed AWS Services

* AWS Graviton-based instances are also available in popular managed AWS
  services such as Amazon Aurora, Amazon Relational Database Service (RDS),
  Amazon MemoryDB for Redis, Amazon ElastiCache, Amazon OpenSearch,
  Amazon EMR, AWS Lambda, and AWS Fargate. These services deliver the price
  performance benefits of AWS Graviton processors while providing a fully
  managed experience.

---

## Best Performance Per Watt In Amazon EC2

* To help customers reduce their carbon footprint, AWS Graviton3 processors,
  just like Graviton2, are more energy efficient. Graviton3-based instances use
  up to 60% less energy for the same performance than comparable EC2 instances.

---

![](https://www.hardwareluxx.de/images/cdn01/F260BA76F4EF46239919AA3A878F6B75/img/AB5F46D6ED954F718D1723F67D849BCA/KeyDB-Graviton2-Benchmarks-1_AB5F46D6ED954F718D1723F67D849BCA.jpg)

---

![](https://www.hardwareluxx.de/images/cdn01/F260BA76F4EF46239919AA3A878F6B75/img/43BAFBFE8BC9411A8C94E442B4E5E6BC/KeyDB-Graviton2-Benchmarks-2_43BAFBFE8BC9411A8C94E442B4E5E6BC.jpg)

---

![](https://static.techspot.com/images2/news/bigimage/2021/04/2021-04-28-image-4-p.webp)

---

![](https://static.techspot.com/images2/news/bigimage/2021/04/2021-04-28-image-6-p.webp)

---

## ARM Graviton3 - Neoverse V1

![](https://images.hothardware.com/contentimages/newsitem/54942/content/Arm_Neoverse_V1_chip_image.jpg)

---

<!-- _class: invert -->

![](https://www.hardwareluxx.de/images/cdn01/E3FA9514CDF5421BBBEBA6E48195C40B/img/0FE1E87FDCFE4EA7BA38CD1170608F80/ARM-Neoverse-V1-N2-Details-00007_0FE1E87FDCFE4EA7BA38CD1170608F80.jpg)