# lacework-iac-demo

[![IaC](https://app.soluble.cloud/api/v1/public/badges/9de1af10-3b06-479d-a9b0-50fa125c31ec.svg?orgId=836920872584)](https://app.soluble.cloud/repos/details/github.com/aedifex/lacework-iac-demo?orgId=836920872584)

This repository contains several sample IaC modules representing several technologies (Terraform, CloudFormation, and CDK) used to convey IaC security scanning principles leveraging Lacework's Soluble tool.

## Terraform Web Server Example

Contains an example [Terraform](https://www.terraform.io/) configuration that deploys a cluster of web servers
(using [EC2](https://aws.amazon.com/ec2/) and [Auto Scaling](https://aws.amazon.com/autoscaling/)) and a load balancer
(using [ELB](https://aws.amazon.com/elasticloadbalancing/)) in an [Amazon Web Services (AWS)
account](http://aws.amazon.com/). The load balancer listens on port 80 and returns the text "Hello, World" for the
`/` URL.

There are several policy violations from low to critical, including lack of best practices, etc. Lacework's Soluble captures these in the compliance evaluations and in some cases provides one-click remediation.

## CloudFormation RDS Cluster

## CDK IAM Policies

## CI/CD Pipeline Integration