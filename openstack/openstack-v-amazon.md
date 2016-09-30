Though Private Cloud and Public Cloud differ in their purposes, here is a quick round up of how OpenStack compares to Amazon's AWS.

This is mainly how cloud service offerings from internal Cloud Service Providers and other OSS projects would look like.

Note the [*] indicates a non-OpenStack component which requires external integration.

|         *Service*      |  *Amazon AWS*          | *OpenStack Project*    |
| ---------------------- | ---------------------- | ---------------------- |
| Identity Management    | IAM                    | Keystone               |
| Virtual Machines       | EC2  + AMI             | Nova + Glance          |
| Object Storage         | S3                     | Swift / Ceph*          |
| Block Storage          | EBS                    | Cinder / Ceph*         |
| Network Services       | VPC                    | Neutron                |
| Load Balancer          | ELB                    | LBaaS  / Octavia       |
| Relational Databases   | RDS                    | Trove                  |
| NoSQL Databases        | SimpleDB               | -                      |
| Resource Templates     | CloudFormation         | Heat                   |
| Hadoop + Big Data      | EMR                    | Sahara / Ambari*       |
| DNS                    | Route 53               | Designate              |
| Monitoring             | CloudWatch             | Ceilometer             |
| Workflow Service       | SWF                    | Mistral                |
| Queue Services         | SQS                    | Zaqar                  |

