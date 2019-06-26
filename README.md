# Basic Cloudformation template examples

##  kubernetesprivate.json
    Template to setup a k8s private environment.   Slightly outdated as I would recommend using EKS now.  

##  kubernetespublic.json
    Template to setup a k8s public environment.   Slightly outdated as I would recommend using EKS now. 

##  vpcbastion.template
    Template to setup a VPC, private and public subnet with a bastion server in the pub subnet.  

##  eksnodescwa.yml
    Template to setup Nodes for an EKS instance.   The nodes will be configured with CWA and a custom memory metric + scale up policy. 