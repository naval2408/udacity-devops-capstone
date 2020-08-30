## Capstone Project : Udacity Cloud Devops

## Overview
This is the final project for the Udacity Cloud Devops Nanodegree. In this project, a Jenkins pipeline is created that implements a Blue/Green deploymenet for a rudimentary service deployed in EKS.

<a name="Steps"></a>
## Things Accomplished
1. Created an Jenkins Server (on a EC2 box) for running the pipeline.
2. Using CloudFormation, created an EKS cluster distributed across public and private subnets over different AZs.
3. A blue green deployement, by just changing the parameters in the file capstone-switch.yml


