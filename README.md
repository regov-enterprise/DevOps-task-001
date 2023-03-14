<p align="center">
  <img src="https://static.wixstatic.com/media/3ba736_be1f7ac0f8bf4e049a5fb6616b18d827~mv2_d_1937_1405_s_2.png/v1/fill/w_220,h_140,al_c,q_85,usm_0.66_1.00_0.01/Regov%20Technologies%202%20PNG_edited.webp" width="200">
</p>

# { "Engineer": "DevOps" }

This exercise is for an end-to-end workload infrastructure on AWS. The workload contains both infrastructure CI/CD and the batch job CI/CD.

## DevOps Tickets

1. Setup an AWS four (4) stages CI/CD pipeline using AWS Cloudformation. The stages (e.g Dev,QA,UAT,Prod) should have manual approvals.

2. Infrastructure as Code (IAC) architecture :

  <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*3BTBz6dXPkYnNI7-sTBWJw.png">


- Write a AWS CDK or Terraform Script to Deploy the following:
  - Infrastructure - (Development Components) Note: Replace Codecommit with Github
  - Batch Job Compoonents
  - Code Deployment from Github to ECR 

## Notes
    * All design, testing, and implementation is at your discretion.
    * If you must test on live account, only test 'free AWS services' available in the stacks.
    * You are required to use free accounts while testing your workload
    * Any cost incured during testing will not be bored by ReGov Technologies Sdn Bhd.
    * Write and include a deployment steps in a README file for the above.

## Submition
1. Upload your codes to Git Repo
2. Update JIRA board on each milestone
3. Inform your Lead and Manager on each step