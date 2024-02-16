# cdev-eks-jenkins

This repository contains an implementation to deploy Jenkins on AWS EKS with Cluster.dev and Helm charts

## Prerequisite

- Install [Cluster.dev CLI](https://docs.cluster.dev/get-started-cdev-aws/)
- [Install Terraform](https://developer.hashicorp.com/terraform/install)
- [Setup AWS credentials](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html)

## How to deploy?

- Update the variables in the `project.yaml`
- Run `cdev apply`