# kafka-eks-infra-setup
A terraform script to create a managed kubernetes cluster on AWS EKS with the spot Instance.This script also gives you an option to setup kafka along with prometheus and kafka-provisioned grafana.
## Prerequisites
Make sure You have installed all of the following prerequisites on your system:
* Kubectl - [Download & Install kubectl](https://kubernetes.io/docs/tasks/tools/) 
* aws-cli - [Download & Install aws-cli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-windows.html) and also configure the awscli.
* Terraform - [Download & Install terraform](https://www.terraform.io/downloads.html)

* Step 1: 
  Clone the repo
  ```
  git clone https://github.com/Adarshkumar14/kafka-eks-infra-setup.git
  ```
  
