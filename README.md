# devops-cicd-project
DevOps CI/CD Pipeline Project
Overview
Automated deployment pipeline using GitHub Actions to deploy a web application to AWS EC2.
Architecture
Developer pushes code → GitHub Actions triggers → SSH into EC2 → Git pull → Website updates automatically
Tech Stack

CI/CD: GitHub Actions
Cloud: AWS EC2
OS: Ubuntu 22.04
Web Server: Nginx
Version Control: Git

How It Works

Developer makes changes to index.html
Pushes code to main branch
GitHub Actions workflow triggers automatically
Pipeline SSH connects to EC2 server
Pulls latest code from GitHub
Nginx serves updated website instantly

What I Learned

Setting up GitHub Actions workflows
Configuring AWS EC2 with proper security groups
SSH key based authentication (passwordless/secure)
Automated deployment without manual intervention
Debugging CI/CD pipeline failures

Live Demo

EC2 Instance: AWS ap-south-1 region
Web Server: Nginx
Auto deployed on every commit


Copy panni GitHub repo → README.md → paste pannuva da!
