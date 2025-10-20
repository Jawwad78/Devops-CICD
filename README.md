# CI/CD Learning (GitHub Actions)

## Overview
This repo was for learning the fundamentals of CI/CD using GitHub Actions. I went through videos covering how to automate build, test, and deploy pipelines, as well as key concepts like actions, workflows and jobs etc.

## Key Concepts Learned
- **CI/CD Fundamentals:** Understanding the full pipeline from committing code to automated deployment.  
- **Workflows:** This is defined in YAML files under `.github/workflows`, containing jobs and steps which will get executed. 
- **Triggers:** Using `on: push`, `pull_request`, and manual triggers to automate when workflows run. (eg. on push would mean after code gets commited)  
- **Jobs and Steps:** Each job runs in a fresh runner; steps define the commands or actions to execute.  ( which are defined in a list)
- **Marketplace Actions:** How to reuse pre-built actions from the GitHub Marketplace instead of rewriting logic.  
- **Custom Actions:** Built custom actions for specific tasks to make it easier
- **Secrets and Variables:** Stored any secrets/sensitive info on Github secrets. Also using variables for non-sensitive configuration.   
 

## Tools that I used:
- GitHub Actions  
- YAML  
- Docker  
- GitHub Secrets and Variables  

## Summary
By completing this module, I learnt how CI/CD pipelines automate the process of testing, building, and deploying applications. I now understand the structure of GitHub workflows and how to build pipelines that run reliably.