# GLAB-908.1.1-DevSecOps

## Overview
In this lab, you'll learn how to use GitHub as a tool for implementing DevSecOps practices in your software development workflow. DevSecOps is a set of principles and practices that integrates security into the software development lifecycle, from planning and coding to testing and deployment.

You'll use GitHub features such as Issues, Pull Requests, Actions, and Packages to implement some basic DevSecOps practices, such as:

- Writing secure code
- Managing security vulnerabilities
- Automating security testing
- Using secure dependencies
- Protecting secrets

### Prerequisites
Before starting this lab, you should have:

- A GitHub account
- Basic knowledge of Git and GitHub
- Basic knowledge of software development and security concepts

### Lab steps

- [ ] Step 1: Fork and clone the lab repository
  Fork the lab repository from https://github.com/ps-manish/GLAB-908.1.1-DevSecOps to your GitHub account.
  Clone the forked repository to your local machine using Git.
  
- [ ] Step 2: Create an Issue for a security requirement
  In the repository, click on the "Issues" tab.
  Click on the "New issue" button.
  Write a description of a security requirement for your project (e.g., "The system should prevent SQL injection attacks").
  Assign the issue to yourself or a team member.
  Add appropriate labels and milestones if needed.
  
- [ ] Step 3: Write secure code
  Open the file src/main/java/com/example/HelloController.java.
  Add a code snippet to prevent SQL injection attacks (e.g., using prepared statements or parameterized queries).
  Commit and push the changes to your forked repository.
  
- [ ] Step 4: Manage security vulnerabilities
  Go to the "Security" tab in your repository.
  Check if there are any detected security vulnerabilities.
  If there are, create an Issue to track the vulnerability.
  Update the vulnerable dependency to a secure version.
  Commit and push the changes to your forked repository.
  
- [ ] Step 5: Automate security testing
  Create a new file test/security-test.sh in your repository.
  Write a shell script that performs a security test on your project (e.g., using a static code analyzer or a vulnerability scanner).
  Add the script as a GitHub Action in .github/workflows/security.yml.
  Test the Action by triggering a manual run or pushing new changes.
  
- [ ] Step 6: Use secure dependencies
  Go to the "Dependencies" tab in your repository.
  Check if there are any outdated or insecure dependencies.
  If there are, update the dependencies to a secure version.
  Commit and push the changes to your forked repository.
  
- [ ] Step 7: Protect secrets
  Create a new secret in your repository settings (e.g., a database password or an API key).
  Modify the src/main/resources/application.properties file to use the secret value (e.g., using the ${SECRET_NAME} syntax).
  Add a GitHub Action in .github/workflows/build.yml that uses the secret value.
  Test the Action by triggering a manual run or pushing new changes.
  
### Lab questions
After completing the lab, try answering these questions in a sentence each

1. What is DevSecOps and why is it important?
2. How can you use GitHub Issues to manage security requirements?
3. How can you write secure code in a GitHub repository?
4. How can you manage security vulnerabilities in a GitHub repository?
5. How can you automate security testing using GitHub Actions?
6. How can you use the "Dependencies" and "Security" tabs in a GitHub repository to manage secure dependencies?
7. How can you protect secrets in a GitHub repository using GitHub Actions?
