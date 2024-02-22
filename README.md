# AWS SysOps Certification Study Notes
Notes taken while studying for AWS SysOps Associate Certification.
- Follow progress by completing notes on syllabus
- Implement labs and mock app

## Guides:

Supporting Material:
https://learn.cantrill.io/p/aws-certified-sysops-administrator-associate

https://www.amazon.com/AWS-Networking-Fundamentals-Understand-Datacenter-ebook/dp/B09PKMWSQ7/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=

## Exercises:
https://github.com/dbgoytia/sysops-training?tab=readme-ov-file

## Practice Exam:
https://portal.tutorialsdojo.com/courses/aws-certified-sysops-administrator-associate-practice-exams/?_gl=1*1213c98*_ga*NTI5NDA4NjMuMTcwNzMyMzA4Nw..*_ga_L96TFJ1R9K*MTcwNzMyMzI0Ny4xLjAuMTcwNzMyMzI0Ny4wLjAuMA..

## GENERAL

### Terraform 
- IAC toll that declare infraestructure. Uses Json to replicate infraestructure to multiple on premisses and cloud providers. 
- Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.
- Terraform creates and manages resources on cloud platforms and other services through their application programming interfaces (APIs). 

Commands Terraform:
fmt - make sure your configuration is syntactically valid and internally consistent
validate - validate configuration
Refresh - TF view what is there in the "real world" looks like 
Plan - what the real work is with the desired config
Apply - Plan is applied to real world.  
Apply the configuration now with the terraform apply command. 
(Go to AWS console, click EC2 from all services list, next click launch instance and find the AMI of an image of your interest.)

Destroy - Plan --> Real World - Decomission resources


## PLAN 

1. Daily - Create notes for each of the sections
    - week 02/19 - Section 1 and 2 + Labs (Sat - Mock)
    - week 02/26 - Section 3 and 4 + Labs (Sat - Mock)
    - week 03/04 - Section 5 and 6 + Labs (Sat - Mock)
    - week 03/11 - Labs + Mock Exams
    - Tentative Test - 20 or 21 march
2. Implement labs from Amazon AWS Skill Builder
3. Review - Implement mvp mentoring app
4. Exercise mock exams - By section and than twice a week

## PENDING
-- Explores logs with implemented application

### Mock Mentoring App Notes
- Simple form to share 
    - What are we discussin today - share topics for agenda (review goals is always there)
    - (Keep historic, integration - calendar)
    - Brainstorm --> (Action Items(Goals) --> Action Steps / Notation (potential to work - need refinement ) / Backburner (to be discarted or put on a chronological list))) Accomplished, Working, Next, Impediments
    - ZProjects priority - Extreme to inactive pag 79
    - Link to references, link to 
    - Networking who can I help, who can help me. Follow up
    - Research on existing collaboration
    - Capture feedback on how to improve collaboration