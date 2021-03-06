---
permalink: mapping-of-amazon-web-services-resources-to-rackspace-resources/
audit_date: '2018-10-05'
title: Mapping of Amazon Web Services resources to Rackspace resources
type: article
created_date: '2013-07-01'
created_by: David Hendler
last_modified_date: '2018-11-06'
last_modified_by: Kate Dougherty
product: Cloud Servers
product_url: cloud-servers
---

**Previous section:** [Migrating to the Rackspace Cloud from Amazon Web Services](/how-to/migrating-to-the-rackspace-cloud-from-amazon-web-services)

The following table maps Amazon&reg; Web Services&reg; (AWS)
infrastructure as a service (IaaS) products to
Rackspace products:

| AWS product | Corresponding Rackspace product |
| --- | --- |
| Amazon Elastic Compute Cloud&reg; (EC2) | [Cloud Servers product and pricing](http://www.rackspace.com/cloud/servers)<br />[Cloud Servers API](https://developer.rackspace.com/docs/cloud-servers/v2/developer-guide/) |
| Amazon Elastic Load Balancing | [Cloud Load Balancers product and pricing](http://www.rackspace.com/cloud/load-balancing)<br />[Cloud Load Balancers API](https://developer.rackspace.com/docs/cloud-load-balancers/v1/developer-guide/)|
| Amazon Virtual Private Cloud&reg; (VPC) | [Cloud Networks product and pricing](https://www.rackspace.com/cloud/networks) |
| Amazon Route 53&reg; | [Cloud DNS product and pricing](https://www.rackspace.com/cloud/dns) |
| AWS Direct Connect&reg; | [RackConnect&reg;](https://www.rackspace.com/cloud/hybrid/rackconnect) |
| Amazon Simple Storage Service&reg; (S3&reg;) | [Cloud Files product and pricing](http://www.rackspace.com/cloud/files)<br />[Cloud Files API](https://developer.rackspace.com/docs/cloud-files/v1/developer-guide/) |
| Amazon Glacier&reg; | [Cloud Backup (with compression)](https://www.rackspace.com/cloud/backup) |
| Amazon Elastic Block Store (EBS) | [Cloud Block Storage product and pricing](http://www.rackspace.com/cloud/block-storage)<br />[Cloud Block Storage API](https://developer.rackspace.com/docs/cloud-block-storage/v1/developer-guide/) |
| AWS Import/Export | Hard Drive Import/Export |
| AWS Storage Gateway | Multiple Partner solutions available |
| Amazon CloudFront&reg; | [Rackspace CDN product and pricing](http://www.rackspace.com/cloud/cdn-content-delivery-network)<br />[Rackspace Content Delivery Network (CDN) API](https://developer.rackspace.com/docs/cdn/v1/developer-guide/) |
| Amazon Relational Database&reg; Service (RDS&reg;) | [Cloud Databases product and pricing](https://www.rackspace.com/cloud/databases)<br />[Cloud Databases API](https://developer.rackspace.com/docs/cloud-databases/v1/developer-guide/) |
| Amazon DynamoDB&reg; | Object Rocket (MongoDB - open) |
| Amazon Simple Email Service&reg; (SES) and Amazon Simple Notification Service&reg; (SNS) | [Mailgun](https://www.mailgun.com/) (Partner Solutions) |
| Elastic Transcoder | [Enterprise Media Processing](https://www.encoding.com/) (Partner Solutions) |
| Identity and Access Management (IAM) console | [Cloud Control Panel](https://login.rackspace.com) |
| AWS CloudWatch&reg; | [Cloud Monitoring product and pricing](http://www.rackspace.com/cloud/monitoring)<br />[Cloud Monitoring API](https://developer.rackspace.com/docs/cloud-monitoring/v1/developer-guide/)  |
| AWS CloudFormation&reg; | Deployments |
| CloudSearch&reg; and Redshift&reg; | Non-Core (Partner Solutions) |

### Mapping of EC2 instance types to Rackspace Cloud instance types

The following table maps Amazon EC2 instance types to equivalent
Rackspace Cloud instance types so that you can select an appropriate
instance size for your Rackspace Cloud Server:

| EC2 instance type   | Rackspace instance type   |
|---------------------|---------------------------|
| Micro:<br />613 MB RAM, up to 2 ECUs, EBS storage, 64 bit | Standard: 512 MB RAM, 20 GB HDD, 1 vCPU<br />1 GB RAM, 40 GB HDD, 1 vCPU<br />Performance: 1 GB RAM, 20 GB SSD, 1 vCPU |
| M1 Small:<br />1.7 GB RAM, 1 ECU, 160 GB local storage, 32 or 64 bit | Standard: 2 GB RAM, 80 GB HDD, 2 vCPUs<br />Performance: 2 GB RAM, 40 GB and 20 GB SSDs, 2 vCPU |
| M1 Medium:<br />3.75 GB RAM, 2 ECUs, 410 GB local storage, 32 or 64 bit | Standard: 4 GB RAM, 160 GB HDD, 2 vCPUs<br />Performance: 4 GB RAM, 40 GB and 40 GB SSDs, 4 vCPU |
| M1 Large:<br />7.5 GB RAM, 4 ECUs, 850 GB local storage, 64 bit | Standard: 8 GB RAM, 320 GB HDD, 4 vCPUs<br />Performance: 8 GB RAM, 40 GB and 80 GB SSDs, 8 vCPU |
| M1 Extra Large:<br />15 GB RAM, 8 ECUs, 1690 GB local storage, 64 bit | Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU |
| M3 Extra Large:<br />15 GB RAM, 13 ECUs, EBS storage, 64 bit | Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU |
| M3 Extra Double Large:<br /> 30 GB RAM, 26 ECUs, EBS storage, 64 bit | Standard: 30 GB RAM, 1200 GB HDD, 8 vCPUs<br />Performance: 30 GB RAM, 40 GB and 300 GB SSDs, 8 vCPU |
| High-Memory Extra Large:<br />17 GB RAM, 6.5 ECUs, 420 GB storage, 64 bit | Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU |
| High-Memory Double Extra Large:<br />34 GB RAM, 13 ECUs, 850 GB local storage, 64 bit | Standard: 30 GB RAM, 1200 GB HDD, 8 vCPUs<br />Performance: 30 GB RAM, 40 GB and 300 GB SSDs, 8 vCPU |

### Support

For more information, contact
[Rackspace Support](https://www.rackspace.com/support).

### Next section

[High-level steps for migrating from Amazon Web Services](/how-to/high-level-steps-for-migrating-from-amazon-web-services)
