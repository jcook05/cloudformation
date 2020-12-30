# Basic Cloudformation template examples

##  kubernetesprivate.json
    Template to setup a k8s private environment.   Slightly outdated as I would recommend using EKS now.  

##  kubernetespublic.json
    Template to setup a k8s public environment.   Slightly outdated as I would recommend using EKS now. 

##  vpcbastion.template
    Template to setup a VPC, private and public subnet with a bastion server in the pub subnet.  

##  eksnodescwa.yml
    Template to setup Nodes for an EKS instance.   The nodes will be configured with CWA and a custom memory metric + scale up policy.  Slightly outdated as I would recommend using 
    cluster autoscaler (https://docs.aws.amazon.com/eks/latest/userguide/cluster-autoscaler.html) now. 

##  vdi-vpc-igw.yaml
    Template to configure a VPC, Subnets, NACLS and IGW for an AWS Workspace VDI Solution.  Includes Private Subnets as well. 

## vdi-ad.yaml
    Template to create a Simple AD for an AWS Workspace VDI Solution

## vdi-example.yaml
    Template to create an AWS Workspace

## cloudtrail.yaml
    Template to create Cloud Trail logs. 

## wazuh-manager.yaml
    Template to create a Wazuh Manager (https://wazuh.com/) Open Source Security Platform instance accessible via a Bastion Host. 