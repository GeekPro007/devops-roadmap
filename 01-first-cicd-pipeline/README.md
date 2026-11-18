# 01 - First CI/CD Pipeline
 
![CI](https://github.com/YOUR_USERNAME/devops-roadmap/actions/workflows/lab01-ci.yml/badge.svg)
 
## Problem
Manually testing code on every change is slow and error-prone.
 
## Objective
Automatically install dependencies and run tests on every push to GitHub.
 
## Tools
Git, GitHub, GitHub Actions, Python, pytest
 
## Architecture
Developer -> git push -> GitHub -> Actions runner
(checkout, setup Python, install, test, upload report) -> pass/fail
 
## How to run locally
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
pytest -v
 
## Troubleshooting
(Describe Breaks A, B, C and D: what I changed, where it failed,
how I recognised it, how I fixed it.)
 
## Cleanup
From the repo root: git rm -r 01-first-cicd-pipeline .github/workflows/lab01-ci.yml
then commit and push. (Do not delete the whole devops-roadmap repo: it holds every lab.)
 
## What I learned
I learned how to create a basic CI/CD pipeline using Github Actions to automate testing whenever code is pushed to Github. I gained practical experience configuring workflow steps, installing dependencies, running pytest and troubleshooting pipeline failures

I also understand how CI/CD helps detec errors early, reduces manual work, and improves software reliability.
