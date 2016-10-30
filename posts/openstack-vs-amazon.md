Though Private Cloud and Public Cloud differ in their purposes, here is a quick round up of how OpenStack compares to Amazon's AWS.

This is mainly how cloud service offerings from internal Cloud Service Providers and other OSS projects would look like.

Note the [*] indicates a non-OpenStack component which requires external integration.

|         *Service*      |  *Amazon AWS*          | *OpenStack Project*    |
| ---------------------- | ---------------------- | ---------------------- |
| Identity Management    | IAM                    | Keystone               |
| Virtual Machines       | EC2                    | Nova	           |
| Containers             | ECS                    | Nova                   |
| Images                 | AMI + VM import/export | Glance                 |
| Object Storage         | S3                     | Swift / Ceph*          |
| Block Storage          | EBS                    | Cinder / Ceph*         |
| Network Services       | VPC                    | Neutron                |
| Load Balancer          | ELB                    | LBaaS  / Octavia       |
| Relational Databases   | RDS                    | Trove                  |
| NoSQL Databases        | DynamoDB               | -                      |
| Resource Templates     | CloudFormation         | Heat                   |
| Hadoop + Big Data      | EMR                    | Sahara / Ambari*       |
| Data Warehousing       | Redshift               | -                      |
| DNS                    | Route 53               | Designate              |
| Monitoring             | CloudWatch             | Ceilometer             |
| Notification Services  | SNS                    | -                      |
| Queue Services         | SQS                    | Zaqar                  |
| Workflow Service       | SWF                    | Mistral                |
| Streaming Data Proc.   | Kinesis                | -                      |
| Media Transcoding      | Elastic Transcoder     | -                      |
| Content Delivery Nets  | CloudFront             | -                      |
| Backup Archival        | Glacier                | -                      |
| Serverless Application | Lambda                 | -                      |
