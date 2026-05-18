# Github
GitHub Version Control Setup Guide
Step 1: Account Creation
Go to GitHub.com.
Sign up using your email and verify your account.
Step 2: Create a Remote Repository
Click the + icon in the top right corner and select New repository.
Give it a name (e.g., my-assignment-repo).
Set it to Public and click Create repository.
Copy the Repository URL (it looks like https://github.com/username/repo-name.git).
Step 3: Local Project Setup
Create a new folder on your computer (e.g., my-assignment).
Open this folder in VS Code.
Create a new text file inside the folder (e.g., readme.txt).
Write some content in the file and save it.
Open the integrated terminal in VS Code (Ctrl + ` or Terminal > New Terminal).
Step 4: Git Commands to Push Code
Run these commands in your VS Code terminal in order:

1. Initialize a local Git repository

git init
2. Add all files in the folder to the staging area

git add .
3. Record your changes with a message

git commit -m "Initial commit"
4. Rename the default branch to 'main'

git branch -M main
5. Link your local folder to the GitHub repo

git remote add origin YOUR_URL
6. Push your code to GitHub

git push -u origin main
