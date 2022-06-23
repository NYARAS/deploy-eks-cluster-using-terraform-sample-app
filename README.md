# deploy-eks-cluster-using-terraform-sample-app

Sample app  deployment using Helm Chart to AWS EKS

## Usage

Check this 
[DevOps Automation with Terraform, AWS and Docker)](https://aws.amazon.com/)
for detailed explanation.

### Environment Variables
These Environment Variables are needed for the pipeline when
runnig Terraform commands.

  * `AWS_DEFAULT_REGION` - AWS region to create the resources
  * `AWS_ACCESS_KEY_ID` - Access Key ID to be used by the pipeline
  to authenticate with your AWS Account
  * `AWS_SECRET_ACCESS_KEY` - Secret Access Key to be used by the
  pipeline to authenticate with your AWS Account
  * `KUBERNETES_CLUSTER` - The name of the EKS cluster to deploy
