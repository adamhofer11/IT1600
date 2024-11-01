# Git Basics

Git is a powerful version control system that helps manage changes in code and collaborate with others.

## Key Concepts
- **Repository (Repo)**: A storage location for your project files and change history.
- **Commit**: A snapshot of your project at a specific point in time.
- **Branch**: A parallel version of your project to work on features or fixes without affecting the main codebase.

## Essential Git Commands

### Initialize a New Repository
Set up a Git repository in your project folder:
```bash
git init
```

### Add Files to Staging
Stage files to prepare them for a commit:
```bash
git add <file-name>
# Or add all files
git add .
```

### Commit Changes
Save staged changes with a descriptive message:
```bash
git commit -m "Initial commit"
```

### Check Status
See the current status of files and which changes are staged:
```bash
git status
```

### View Commit History
See all previous commits in the repository:
```bash
git log
```

## Example Workflow
```bash
git init
git add .
git commit -m "Initial commit"
git status
```

---

**Navigation**  
[Previous: Introduction](introduction.md) | [Home](README.md) | [Next: Markdown Syntax](markdown-syntax.md)

