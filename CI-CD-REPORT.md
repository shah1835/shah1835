# CI/CD Pipeline Report

## Student Information
- Name: Shariq Ali
- Date: 11/8/2025
- Repository: https://github.com/shah1835/shah1835.git
- Live URL: https://shah1835.github.io/shah1835/

## Deployment History
Check the Actions tab for complete deployment history.

### Iteration Summary
1. **Initial Deployment**
   - Commit: Add portfolio website
   - Time to Deploy: 8 seconds
   - Status: Success

2. **Iteration 1: Personalization**
   - Commit: Personalize Content
   - Changes Made: Replace all instances of "Your Name" with my name
                   Update the university name in about.html
                   Added actual graduation year
   - Deployment Time: 10 seconds

3. **Iteration 2: Deploy Info**
   - Commit: Add Deployment Information
   - Changes Made: Created a new file deply-info.json
                   Then updated projects.html and added the fourth project card
   - Deployment Time: 8 seconds

4. **Iteration 3: Feature Branch**
   - PR Number: #1
   - Branch: feature/add-contact
   - Deployment triggered by: Pull Request merge

## CI/CD Understanding

### What is CI/CD?
CI/CD, Continuous Integration and Continuous Delivery/Deployment, is a software development practice that uses automation to build, test, and deploy code changes more frequently and reliably. It streamlines the software development lifecycle by automating the processes of integrating code from multiple developers, verifying its quality, and delivering it to production.

### Benefits Observed
1. Faster development and deployment of code as changes are automatically built, tested, and deployed, reducing manual effort.This allows teams to release updates and new features more frequently.
2. Improves code quality and reliability through automated testing and ensures that bugs are detected early in the development process.Each integration is verified before deployment, reducing the risk of failures in production.
3. Enhanced collaboration and efficiency as it allows developers to integrate code frequently without worrying about breaking the main branch. This encourages teamwork and consistent workflows across the project.

### Challenges Faced
The issue I faced was with the branch as I was not quite sure if it worked so I did another pull request which made a revert of the feature/contact which I deleted so please if you want to compare the code of the branch with main please use the pull request #1 and not the pull request #2.

### Real-World Application
In larger software projects, a CI/CD pipeline becomes even more important because it helps manage the complexity that comes with many developers, components, and frequent updates. The pipeline will automatically integrate their code, ensuring compatibility and reducing merge conflicts, this ensures that new changes don’t break existing functionality, even in large, interconnected systems. This will guarantee that every release follows the same quality checks and reduces deployment risks. Overall this keeps large projects agile and responsive to change.

## Screenshots
### Initial Website
![](<initial home.png>) ![](<initial about.png>)  ![](<initial projects.png>)
### Action Tab
![](<Action tab.png>)
### Final Website
![](<home page.png>) ![](<about page.png>) ![](<projects page.png>)