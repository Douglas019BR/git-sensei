🇺🇸 [English](./COMMANDS.md) | 🇧🇷 [Português](./pt-br/COMMANDS.md)

# Git Commands

Think of these commands as magic spells you can use to control your project's history.

## The Three Areas

Before we learn the commands, you need to know about the three secret areas where your work lives:

1. **The Working Directory:** This is your playground! It's where you create and edit your files. (local)
2. **The Staging Area:** This is like a waiting room. Before you save your work, you put it in the staging area to get it ready. (local before being pushed)
3. **The Repository (or Repo):** This is the treasure chest where you store all the saved versions of your project. (remote)

---

## Basic Commands

### `git init`

- **What it does:** This is the first spell you cast. It creates a new, empty treasure chest (repository) in your project folder.
- **How to use it:** `git init`

### `git diff`

- **What it does:** This spell shows the difference between the files you modified and the original files. This shows the changes that you made.
- **How to use it:**
  - `git diff <file_name>` (to see the difference in one file)
  - `git diff` (to show all differences in your new work)

### `git add`

- **What it does:** This spell moves your work from your playground (Working Directory) to the waiting room (Staging Area).
- **How to use it:**
  - `git add <file_name>` (to add one file)
  - `git add .` (to add all your new work) Be careful with this—it's not a good practice to add all files at once because you might add some files that you changed unintentionally and you won't review these changes before adding to stage. It's not prohibited, but use with care.

### `git commit`

- **What it does:** This is the most important spell! It takes everything in the waiting room (Staging Area) and saves it as a new version in your treasure chest (Repository). You also leave a message to remember what you changed. The commit will create a checkpoint in the version history!
- **How to use it:** `git commit -m "Your descriptive message here"`
- **Example:** `git commit -m "feat-1234 Create a middleware for error handling"`

### `git status`

- **What it does:** This spell tells you what's happening in your project. It shows you which files are new, which have been changed, and which are ready to be saved.
- **How to use it:** `git status`

### `git log`

- **What it does:** This spell shows you all the versions you've saved in your treasure chest (Repository). It's like looking at a timeline of your project. It's like a commit history.
- **How to use it:** `git log`

---

## Intermediate Commands

### `git branch`

- **What it does:** Imagine your project is a tree. A branch is a new path you can take to try out new ideas without changing the main trunk of the tree. You can do whatever you want in your branch—don't worry! As long as you don't push these changes to official branches (dev, main, master... each project has its own), the code is just yours.
- **How to use it:**
  - `git branch` (to see all the branches)
  - `git branch <branch_name>` (to create a new branch)

### `git checkout`

- **What it does:** This spell lets you switch between different branches or versions of your project.
- **How to use it:** `git checkout <branch_name>`

### `git merge`

- **What it does:** After you've worked on a branch and you're happy with your changes, you can use this spell to combine your branch back into the main trunk of the tree. I really recommend doing the merge on the console (GitHub or GitLab) because you can review the changes and (now) use GenAI agents to review your changes too.
- **How to use it:** `git merge <branch_name>`

---

## Advanced Commands (for when you're a Git wizard!)

### `git pull`

- **What it does:** If you're working with friends on the same project, this spell fetches the latest changes from a remote treasure chest (like on GitHub) and merges them into your local project.
- **How to use it:** `git pull`

### `git push`

- **What it does:** This spell sends your saved changes from your local treasure chest to a remote treasure chest (like on GitHub) so your friends can see your work.
- **How to use it:** `git push`

### `git rebase`

- **What it does:** This is a powerful spell that lets you rewrite your project's history. It's like going back in time and changing the order of events. Use this one with care!
- **How to use it:** `git rebase <branch_name>`

### `git clone`

- **What it does:** This spell makes a copy of a remote treasure chest (like from GitHub) on your own computer.
- **How to use it:** `git clone <url_of_the_repository>`

## What's Next?

Now that you know the basic commands, let's learn about some more advanced concepts that will make you a Git master!

- [Advanced Git Concepts](./ADVANCED_CONCEPTS.md)
