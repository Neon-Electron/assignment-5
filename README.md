# Lab Experiment 5: How to Use Git Effectively

A comprehensive guide to understanding version control with Git, covering essential commands and workflows for effective code management.

## 📋 Objectives

This lab experiment aims to help you:

1. Understand the purpose of version control systems
2. Learn how to set up and configure Git
3. Practice essential Git commands for managing code effectively
4. Explore collaboration workflows with branching and merging

## 🔑 Key Git Concepts

- **Repository (repo)**: A storage location for your project
- **Commit**: A snapshot of your project at a certain time
- **Branch**: A parallel version of your project for isolated development
- **Merge**: Integrating changes from one branch into another
- **Remote**: A version of your project hosted online (e.g., GitHub)

## 🚀 Getting Started

### Step 1: Install and Configure Git

Check if Git is installed:
```bash
git --version
```

Configure your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Step 2: Create a New Repository

```bash
mkdir my_project
cd my_project
git init
```

### Step 3: Add and Commit Files

```bash
echo "Hello Git" > file.txt
git status
git add file.txt
git commit -m "Initial commit with file.txt"
```

### Step 4: Create and Switch Branches

```bash
git branch new_feature
git checkout new_feature
```

### Step 5: Merge Branches

```bash
git checkout main
git merge new_feature
```

### Step 6: Connect to Remote Repository

```bash
git remote add origin https://github.com/username/my_project.git
git push -u origin main
```

## 📖 Command Reference

| Command | Description |
|---------|-------------|
| `git init` | Initialize a repository |
| `git status` | Show changes status |
| `git add <file>` | Stage file changes |
| `git commit -m "msg"` | Save staged changes with a message |
| `git branch` | List branches |
| `git checkout <branch>` | Switch branches |
| `git merge <branch>` | Merge a branch into current branch |
| `git push` | Upload local changes to remote |
| `git pull` | Download changes from remote |

## 💡 Tips

- Always check `git status` before committing to see what changes will be included
- Write clear, descriptive commit messages
- Create branches for new features to keep your main branch stable
- Pull changes from remote before pushing to avoid conflicts

## 📚 Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Git Cheat Sheet](https://training.github.com/downloads/github-git-cheat-sheet/)

## 📝 License

This lab experiment is for educational purposes.

---

**Happy Coding! 🎉**