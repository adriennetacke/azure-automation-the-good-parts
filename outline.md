# Azure Automation: The Good Parts

## Typical Workflow
1. Code
2. Push to remote
3. Code Review
4. Merge into master pending following steps pass (dev/qa/staging/prod):
    - Run Unit Tests
    - Run Automated UI Tests
    - Run Integration Tests
5. Functional testing (QA) 
6. Approval to higher environments
7. Approval to release
8. Release created
9. It's in PROD!

## Which steps to automate?

## Which CAN we automate?

## What still needs manual intervention?
- Approvals to higher enviroments
- Code review processes (hopefully!)

## Context of Infrastructure

- DEV
- QA
- PROD

Several projects, each housed in their own repo

## Pull Request Policies
- At least 2
- Cannot approve your own
- 

## Automate Builds

## Automate Releases

## 