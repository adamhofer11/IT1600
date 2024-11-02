# Advanced Topics

In this section, we explore some advanced concepts to enhance your understanding of markdown and Git workflows.

## Table of Contents
- **Customizing Markdown**: Learn about extensions and tools to extend markdown's functionality.
- **Advanced Git Commands**: Commands like `git rebase`, `git stash`, and `git cherry-pick` for complex workflows.
- **GitHub Actions**: Automate tasks in your repository using GitHub’s powerful CI/CD tool.

### Customizing Markdown
Extensions like **Markdown Extra** and **GitHub Flavored Markdown** provide additional syntax options to enhance document formatting.

### Advanced Git Commands
1. **git rebase**: Reapply commits on top of another base.
   ```bash
   git rebase main
   ```
2. **git stash**: Temporarily save your work without committing it.
   ```bash
   git stash
   ```
3. **git cherry-pick**: Apply a specific commit from one branch to another.
   ```bash
   git cherry-pick <commit-hash>
   ```

### GitHub Actions
GitHub Actions allows you to automate workflows like testing, building, or deploying your code. You define these workflows using YAML files in the `.github/workflows` directory.

---

**Navigation**  
[Previous: Markdown Syntax](markdown-syntax.md) | [Home](README.md)
