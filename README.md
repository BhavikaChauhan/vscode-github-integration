GitHub and VS Code Integration Project
Overview
This project demonstrates how to integrate GitHub with Visual Studio Code (VS Code) by creating and managing a repository. It covers every step, from initializing a Git repository locally using Git Bash, linking it with GitHub, and managing the repository in VS Code.

Features
Set up a Git repository locally using Git Bash.
Push the repository to GitHub.
Seamlessly integrate and manage the repository in VS Code.
Commit and push changes using VS Code.
Prerequisites
Before starting, ensure the following tools are installed on your system:

Git: Download and Install Git
GitHub Account: Sign up for GitHub
VS Code: Download and Install VS Code
GitHub Extensions for VS Code:
GitHub Pull Requests and Issues
GitLens – Git Supercharged


Steps to Replicate 
1. Initialize a Local Repository
Open Git Bash and navigate to your desired directory:
cd ~/Desktop
mkdir vscode-github-integration
cd vscode-github-integration
Initialize a Git repository and add a README file:
git init
echo "# GitHub and VS Code Integration Project" > README.md
git add README.md
git commit -m "Initial commit: Add README.md"

2. Create a Remote Repository on GitHub
Log in to GitHub and create a new repository with the name vscode-github-integration.
Copy the repository URL (e.g., https://github.com/your-username/vscode-github-integration.git).

3. Connect Local and Remote Repositories
Link the local repository to the GitHub repository
git remote add origin https://github.com/your-username/vscode-github-integration.git
git branch -M main
git push -u origin main

4. Open the Repository in VS Code
Open VS Code and navigate to the repository folder (File > Open Folder).
Install the GitHub-related extensions:
GitHub Pull Requests and Issues
GitLens – Git Supercharged

5. Test the Integration
Make a change to README.md:

6. Verify and Share the Repository
Go to your GitHub repository to confirm the changes.
Share the repository link with others to showcase your work.

#Purpose  
This project demonstrates how to integrate GitHub with VS Code.

In VS Code:
Go to the Source Control tab.
Stage the changes, commit them, and push to GitHub.

Initializing a Git repository.
Linking the repository to GitHub.
Making and pushing changes from VS Code.


Author
Bhavika



Feel free to share feedback or contribute to this project!