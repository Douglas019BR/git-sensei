🇺🇸 [English](./LESSON_ONE.md) | 🇧🇷 [Português](./pt-br/LESSON_ONE.md)

# Lesson 1: Introduction to Git and GitHub 👋

## What is Git? 🤷♂️
Git is a distributed version control system that helps you track changes in your code. It allows multiple people to work on the same project without interfering with each other's work.

## Why Use Git? 🎯
- Track changes to your code over time
- Collaborate with others without conflicts
- Maintain different versions of your project
- Revert to previous versions if needed
- Work offline and sync later

## Getting Started 🚀

### Installation 💻
```bash
# For Ubuntu/Debian
sudo apt-get install git

# For macOS (using Homebrew)
brew install git

# For Windows
# Download from https://git-scm.com/download/win
```

### Basic Configuration ⚙️
```bash
# Set your username
git config --global user.name "Your Name"

# Set your email
git config --global user.email "your.email@example.com"
```

### Creating Your First Repository 📁
```bash
# Create a new directory
mkdir my-first-project
cd my-first-project

# Initialize a Git repository
git init
```

### Understanding the Basic Workflow 🔄

1. **Working Directory**: Where you create, edit, delete, and organize files
2. **Staging Area**: Where you prepare changes for a commit
3. **Repository**: Where Git permanently stores changes as commits

### Basic Commands 📝

```bash
# Check the status of your repository
git status

# Add files to the staging area
git add filename.txt   # Add a specific file
git add .              # Add all files

# Commit your changes
git commit -m "My first commit message"

# View commit history
git log
```

## Practice Exercise 🏋️♀️
1. Create a new repository
2. Add a README.md file with a brief description
3. Commit the file
4. Make changes to the README.md
5. Commit the changes
6. View your commit history

Remember, Git is a powerful tool that gets easier with practice. Don't worry if it feels complicated at first—we'll build your skills step by step! 🌱

## Problems and Support 🆘

In case of trouble, use the [issue section](https://github.com/git-sensei/git-sensei/issues) to ask questions or report a problem. This is a good practice and it's used by most repositories. It's also a good practice to search existing issues before creating a new one, in case someone has asked the same or similar question. You can try the same solution or reply with a comment in the existing issue.

## What's Next?

Now that you know about the basic commands, let's continue exploring this fantastic world.

- [Second lesson](./LESSON_TWO.md)
