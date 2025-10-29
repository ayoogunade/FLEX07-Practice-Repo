# FLEX07 GitHub Practice Repository

Welcome to the FLEX07 Practice Repository! This repository is designed to help students learn the fundamentals of Git and GitHub through hands-on practice.

## Purpose

This is a simple practice environment where students can:
- Learn basic Git commands
- Practice creating branches
- Make commits and push changes
- Resolve merge conflicts
- Collaborate with others using GitHub

## Repository Contents

- `produce.txt` - A simple text file containing a list of fruits and vegetables
- `.gitignore` - Configuration file for ignoring certain files in Git

## Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
cd FLEX07-Practice-Repo
```

### 2. Check the Status
```bash
git status
```

### 3. View Commit History
```bash
git log --oneline
```

## Practice Exercises

### Exercise 1: Make Your First Commit
1. Add a new fruit or vegetable to `produce.txt`
2. Stage your changes: `git add produce.txt`
3. Commit with a message: `git commit -m "Added [item name]"`
4. Push to GitHub: `git push`

### Exercise 2: Create a Branch
1. Create a new branch: `git branch <your-name>`
2. Switch to your branch: `git checkout <your-name>`
   - Or use one command: `git checkout -b <your-name>`
3. Make changes to `produce.txt`
4. Commit your changes
5. Push your branch: `git push -u origin <your-name>`

### Exercise 3: Merge Changes
1. Switch back to main: `git checkout main`
2. Merge your branch: `git merge <your-name>`
3. Push the merged changes: `git push`

### Exercise 4: Handle Merge Conflicts
1. Work with a partner and both edit the same line in `produce.txt`
2. Attempt to merge - you'll encounter a conflict!
3. Open the file and resolve the conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`)
4. Stage the resolved file: `git add produce.txt`
5. Complete the merge: `git commit`

## Common Git Commands Reference

| Command | Description |
|---------|-------------|
| `git status` | Check the status of your working directory |
| `git add <file>` | Stage changes for commit |
| `git commit -m "message"` | Commit staged changes |
| `git push` | Push commits to remote repository |
| `git pull` | Pull latest changes from remote |
| `git branch` | List all branches |
| `git checkout <branch>` | Switch to a different branch |
| `git merge <branch>` | Merge a branch into current branch |
| `git log` | View commit history |

## Tips for Success

- Always `git pull` before starting new work to get the latest changes
- Write clear, descriptive commit messages
- Commit often and in small, logical chunks
- Don't be afraid to experiment - that's what this repo is for!
- If you make a mistake, ask for help - we're all learning together

## Need Help?

If you get stuck or encounter issues:
1. Check `git status` to see what state your repository is in
2. Review the error message carefully
3. Ask your instructor or classmates for assistance
4. Remember: everyone makes mistakes when learning Git - it's part of the process!

## Learning Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---

Happy coding and happy collaborating!
