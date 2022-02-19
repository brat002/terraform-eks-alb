# Sample Terraform project to deploy EKS cluster
1. set cluster-region variable
2. set users map in terraform.tfvars to access the cluster from aws console
3. define region
4. Install AWS Load Balancer Controller: https://artifacthub.io/packages/helm/aws/aws-load-balancer-controller
5. import kubectl config `aws eks update-kubeconfig --region region-code --name cluster-name`

How to check:

Run game 2048 from example https://aws.amazon.com/premiumsupport/knowledge-center/eks-alb-ingress-controller-setup/

https://learnk8s.io/terraform-eks