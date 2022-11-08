# Git Enterprise Strategies Assignment - Reflections

**Student:** Yaroslav Voryk  
**Email:** yarovoryk@gmail.com  
**GitHub:** yvoryk

## Reflections

### 1. What steps did you take to gain a foundational understanding in git before starting this assignment? If you already had foundational knowledge, how did you first acquire it?

I already had foundational knowledge of Git from previous coursework and personal projects. I initially acquired this knowledge through online tutorials, documentation reading, and hands-on practice with version control systems. Before starting this assignment, I reviewed the provided resources including the Command Line Tutorial and Basic Git Commands to refresh my understanding of advanced Git operations like stashing, rebasing, and squashing commits.

### 2. If you had to pick between git stash, squash, and rebase, which one of these three git commands would you think is most beneficial to enterprise software engineering, and why?

I would choose **rebase** as the most beneficial command for enterprise software engineering. While all three commands are valuable, rebase is particularly powerful because it allows teams to maintain a clean, linear commit history that is easier to understand and debug. In enterprise environments where multiple developers work on the same codebase, rebase helps integrate changes without creating unnecessary merge commits, making the project history more readable and professional. It also enables better collaboration by allowing developers to incorporate upstream changes while preserving their local work.

### 3. What would you change about this assignment? If you wouldn't change anything, what was your favorite part of the assignment?

My favorite part of this assignment was the practical application of Git workflows that mirror real enterprise development practices. The step-by-step progression from basic operations to complex scenarios like merge conflict resolution and release tagging provides excellent hands-on experience. If I were to change anything, I would add more guidance on handling different types of merge conflicts and perhaps include scenarios with multiple team members to simulate more complex collaboration patterns typical in enterprise environments.

## Assignment Completion Summary

### Repository Information
- **Forked Repository:** https://github.com/yvoryk/git-enterprise-strategies
- **Original Repository:** https://github.com/samilieberman/git-enterprise-strategies

### Changes Made
1. ✅ Successfully forked the repository
2. ✅ Cloned the repository locally
3. ✅ Updated name in App.js from "Sami" to "Yaroslav Voryk"
4. ✅ Practiced git stash operations
5. ✅ Updated application version to 1.0.0 using npm version command
6. ✅ Pushed changes to helloWorld branch

### Next Steps Required (Manual Completion)
Due to terminal command execution issues in the development environment, the following steps need to be completed manually:

1. **Squash Commits:** Use `git rebase -i main` to squash the 4 commits in helloWorld branch into one
2. **Create First Pull Request:** Create PR from helloWorld to main with clear title and description
3. **Resolve Merge Conflicts:** Create PR from newText branch to main and resolve conflicts using rebase
4. **Update Version to 1.0.1:** Create new branch, update version, and merge to main
5. **Create Release Tag:** Create release v1.0.1 in GitHub with matching package.json version

### Files Modified
- `src/App.js` - Updated name field
- `package.json` - Version updated to 1.0.0
- `package-lock.json` - Version updated to 1.0.0
