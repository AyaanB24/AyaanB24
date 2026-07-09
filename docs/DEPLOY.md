# Deployment Guide

## Step 1: Create a GitHub repository
Create a new repository with the same name as your GitHub username. For example, if your username is `AyaanB24`, create a repository named `AyaanB24`.

## Step 2: Push the files
Initialize a git repository and push the code to GitHub:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/AyaanB24/AyaanB24.git
git push -u origin main
```

## Step 3: Configure GitHub Actions permissions
1. Go to your repository settings
2. Navigate to "Actions" → "General"
3. Under "Workflow permissions", select "Read and write permissions"
4. Check "Allow GitHub Actions to create and approve pull requests"

## Step 4: Create DSA repository
Create a repository named `DSA` and organize your problems into `Easy`, `Medium`, and `Hard` directories.

## Step 5: Test the workflows
Go to "Actions" tab in your repository and manually trigger the workflows to test them.

## Step 6: Customize
- Replace links in README.md with your actual links
- Update profile information as needed
