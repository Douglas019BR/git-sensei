🇺🇸 [English](./LESSON_THREE.md) | 🇧🇷 [Português](./pt-br/LESSON_THREE.md)

# Lesson 3: Forking and Contributing to Projects 🍴

## What You'll Learn 🎯
In this lesson, you'll learn how to contribute to existing projects by:
- Forking repositories
- Making changes
- Creating pull requests

## What is Forking? 🤔
Forking creates a personal copy of someone else's project. It allows you to freely experiment with changes without affecting the original project.

## Step-by-Step Guide 📝

### 1. Fork a Repository 🍴
1. Go to the GitHub repository you want to contribute to
2. Click the "Fork" button in the top-right corner of the page
3. Select where to fork the repository (usually your personal account)
4. Wait for GitHub to create your fork

### 2. Clone Your Fork 📥
```bash
# Replace USERNAME with your GitHub username
# Replace REPOSITORY with the repository name
git clone https://github.com/USERNAME/REPOSITORY.git

# Navigate into the repository folder
cd REPOSITORY
```

### 3. Create a Branch 🌿
```bash
# Create a new branch for your changes
git checkout -b my-new-feature

# This is shorthand for:
# git branch my-new-feature
# git checkout my-new-feature
```

### 4. Make Changes ✏️
1. Add or modify files in your local repository
2. Create a new file or edit existing ones

### 5. Commit Your Changes 💾
```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "Add new feature: description of changes"
```

### 6. Push to Your Fork 📤
```bash
git push origin my-new-feature
```

### 7. Create a Pull Request 🔄
1. Go to your fork on GitHub
2. Click the "Compare & pull request" button
3. Ensure the base repository is the original and the head repository is your fork
4. Add a title and description explaining your changes
5. Click "Create pull request"

## Best Practices for Pull Requests 🌟
- Keep changes focused and specific
- Write clear commit messages
- Follow the project's contribution guidelines
- Be responsive to feedback and be prepared to make additional changes

## Practice Exercise 🏋️💻
1. Go to the [SendScriptWhatsApp](https://github.com/Douglas019BR/SendScriptWhatsApp) repository. This repo is a collection of scripts to send large messages on WhatsApp row by row.
2. Fork the repository
3. Add a simple file following the model of [existing files](https://github.com/Douglas019BR/SendScriptWhatsApp/tree/main/scripts)
4. Commit your file and create a pull request to the original repository
5. Engage with any feedback you receive

Remember, contributing to open-source projects is a great way to improve your skills and join the developer community! 🚀

## Common Issues and Solutions 🔧

### Fork Not Appearing
- Refresh the page after forking
- Check if the fork was created in your account

### Pull Request Conflicts
- Your branch might be behind the main branch
- Pull the latest changes from the original repository before creating your PR

### Permission Denied
- Make sure you're pushing to your fork, not the original repository
- Check your authentication credentials

## Congratulations! 🎉

You've completed the Git Sensei course! You now have the fundamental skills to:
- Use Git for version control
- Work with GitHub repositories
- Collaborate with other developers
- Contribute to open-source projects

Keep practicing these skills, and you'll become a true Git master! 🥋

## Problems and Support 🆘

In case of trouble, use the [issue section](https://github.com/Douglas019BR/git-sensei/issues) to ask questions or report a problem. This is a good practice and it's used by most repositories. It's also a good practice to search existing issues before creating a new one, in case someone has asked the same or similar question. You can try the same solution or reply with a comment in the existing issue.

## What's Next?

- Explore more advanced Git features like `git stash`, `git cherry-pick`, and `git bisect`
- Learn about Git workflows like GitFlow or GitHub Flow
- Practice contributing to real open-source projects
- Consider learning about continuous integration and deployment (CI/CD)
