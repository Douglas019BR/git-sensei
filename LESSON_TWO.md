🇺🇸 [English](./LESSON_TWO.md) | 🇧🇷 [Português](./pt-br/LESSON_TWO.md)

# Lesson 2: Working with Remote Repositories 🌐

## What You'll Learn 🎯
In this lesson, you'll learn how to:
- Connect your local repository to GitHub
- Push and pull changes
- Clone existing repositories

## GitHub: Git in the Cloud ☁️
GitHub is a platform that hosts Git repositories online, making it easy to:
- Back up your code
- Collaborate with others
- Share your projects with the world
- Contribute to open-source software

## Creating a GitHub Account 📝
1. Go to [github.com](https://github.com)
2. Sign up for a free account
3. Verify your email address

## Creating a New Repository on GitHub 🆕
1. Click the "+" icon in the top-right corner
2. Select "New repository"
3. Name your repository
4. Add an optional description
5. Choose public or private
6. Click "Create repository"

## Connecting Your Local Repository to GitHub 🔗
Use the local repository created in lesson one.

```bash
# Add a remote
git remote add origin https://github.com/USERNAME/REPOSITORY.git

# Verify the remote was added
git remote -v
```

## Pushing Your Code to GitHub 📤

```bash
# Push your commits to GitHub
git push -u origin main

# After the first push, you can simply use:
git push
```

## Cloning an Existing Repository 📥
Explore GitHub projects like you explore social media. Search for themes, people, technologies, read the README.md of projects, let your curiosity guide you. Choose a project to clone—any project.

```bash
# Clone a repository from GitHub
git clone https://github.com/USERNAME/REPOSITORY.git

# This creates a new directory with the repository name
```

## Pulling Changes from GitHub 🔄

```bash
# Get changes from GitHub
git pull origin main
```

## Working with Branches 🌿

```bash
# Create a new branch
git branch feature-branch

# Switch to the branch
git checkout feature-branch

# Or create and switch in one command
git checkout -b feature-branch

# Push the branch to GitHub
git push -u origin feature-branch
```

## Practice Exercise 🏋️♀️
1. Create a new repository on GitHub
2. Connect your local repository from Lesson 1
3. Push your code to GitHub
4. Make changes on GitHub (edit a file directly on the website)
5. Pull the changes to your local repository
6. Create a new branch, make changes, and push it to GitHub

## Common Issues and Solutions 🔧

### Authentication Failed
- Make sure you're using the correct username and password
- Consider using SSH keys or a personal access token for more security

### Push Rejected
- Your local repository might be behind the remote
- Try pulling changes first with `git pull`

Remember, GitHub makes collaboration possible and provides a backup of your code. It's an essential tool for modern developers! 🚀

## What's Next?

Now that you know about GitHub, let's learn about how to contribute to a project.

- [Third lesson](./LESSON_THREE.md)
