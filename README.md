* DevOps Project: Kubernetes and GitOps Automation

This repository documents the step-by-step implementation of an industry-level DevOps project using Kubernetes, GitOps, and modern deployment tools. The project demonstrates
how to deploy applications on AWS EKS, automate CI/CD pipelines, implement Istio service mesh, and monitor applications using advanced tools.


Here's a clean and well-organized README.md file for your GitHub project. The steps have been arranged sequentially according to the project workflow:

DevOps Project: Kubernetes and GitOps Automation
This repository documents the step-by-step implementation of an industry-level DevOps project using Kubernetes, GitOps, and modern deployment tools. The projectdemonstrates 
how to deploy applications on AWS EKS, automate CI/CD pipelines, implement Istio service mesh, and monitor applications using advanced tools.

Prerequisites
Ensure you have the following tools installed:Deplu

AWS CLI (https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
eksctl (https://github.com/eksctl-io/eksctl/releases)
kubectl (https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/)
Git bash (https://git-scm.com/downloads)
Istio (https://github.com/istio/istio/releases)

* Note :- Keep all the binary files in same path so you can use them with ease from all directories of local server.

* Project Steps :-
1. Congifure your aws account with the help of AWS ClI.
2. "aws configure" write this command to configure the credentials of your aws account in your local system.
3. Deploy the cluser in AWS eks with following commaand "eksctl create cluster --name devopsproject".
4. Deyplay your web app withfollowing command "kubectl apply -f https://raw.githubusercontent.com/vimallinuxworld13/eks_istio_bookinfo_app/refs/heads/master/bookinfo.yaml
"
