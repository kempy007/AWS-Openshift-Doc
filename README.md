# AWS-Openshift-Doc
* Demo detailing architecture and deployment story to spinup openshift on AWS, using packer > coreos > docker > jenkins > terraform > ansible.

* So a slightly more complicated process than Azure Shell or GCP Shell invoking just the terraform script and ansible job.

## Architecture 
![.](https://github.com/kempy007/AWS-Openshift-Doc/blob/master/AWS-Openshift-Architecture.jpg)

## Deployment Story
![.](https://github.com/kempy007/AWS-Openshift-Doc/blob/master/AWS-Openshift-Architecture-DeploymentStory.jpg)

## Actions List
- [ ] A1. Packer build
- [X] A2. Terraform + AWS CLI Docker build
- [X] A3. AWS Terraform build
- [ ] A3.1 Todo, add ASG
- [X] A4. Jenkinsfile build
- [ ] A5. Jenkins conf
- [ ] A6. Ansible support for ASG, create custom AMI

## Test List
- [ ] A1. Tested 
- [X] A2. Tested (1 hr)
- [X] A3. Tested  (2+ days)
- [ ] A3.1 Tested
- [X] A4. Tested (2 1/2days)
- [ ] A5. Tested
- [ ] A6. Tested

## Repository List
- A1. 
- A2.
- A3. 
- A4. 
- A5. 
