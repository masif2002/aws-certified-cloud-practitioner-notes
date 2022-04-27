## AWS Cloud Use Cases
* AWS enables you to build sophisticated, scalable applications
* Applicable to a diverse set of industries
* Use cases include
    * Enterprise IT, Backup & Storage, Big Data analytics
    * Website hosting, Mobile & Social Apps
    * Gaming

## AWS Global Infrastructure
> ** Possible Question Area (PQA) ** 
* AWS Regions
* AWS Availability Zones 
* AWS Data Centers 
* AWS Edge Locations / Points of Presence

## AWS Regions 
* AWS has **Regions** all around the world
* AWS Regions consist of multiple, isolated, and physically separate _Availability Zones_ within a geographic area.
* Names can be us-east-1, eu-west-3… 
* A region is a **cluster of data centers**
* Most AWS services are region-scoped
![](img/aws-region.png)  

## AWS Availability Zones
* Availability zones constitute a **region**
    * Each region has many availability zones (usually 3, min is 2, max is 6). 
* **Each availability zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity**
* They’re separate from each other, so that they’re isolated from disasters and they’re connected with high bandwidth, ultra-low latency networking
## AWS Points of Presence (Edge Locations)
* Amazon has 216 Points of Presence (205 Edge Locations & 11 Regional
Caches) in 84 cities across 42 countries
* Content is delivered to end users with lower latency

## AWS services
### **Global Services**
* Identity and Access Management (IAM)
* Route 53 (DNS service)
* CloudFront (Content Delivery Network)
* WAF (Web Application Firewall)
### **Region-scoped Services** 
* Amazon EC2 (Infrastructure as a Service)
* Elastic Beanstalk (Platform as a Service)
* Lambda (Function as a Service)
* Rekognition (Software as a Service)

> Most AWS services are Region-scoped 
## Shared Responsibility Model
![](img/shared-responsibility-model.png)  