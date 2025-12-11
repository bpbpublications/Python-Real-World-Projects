
# Project: Python Real World Mini Projects - Chapter 2
## Terminal Commands Summary

### Project Initialization & Git Setup
```bash
mkdir todo_cli
cd todo_cli
git init
```

### Git Configuration (Once per system)
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Project Setup (File Tracking & Initial Commit)
```bash
git add .
git commit -m "Initial project setup with structure and README"
```

### Installing the Project Locally (Development Mode)
```bash
pip install -e .
```

### Using the CLI Application
```bash
todo add "Read Git tutorial"
todo list
todo complete 1
todo delete 1
```

### Run Unit Tests
```bash
pytest tests/
```

### Branching
```bash
git checkout -b feature-color-output
git add src/todo_cli/cli.py
git commit -m "Add color to CLI output"

git checkout -b feature-due-dates
git add .
git commit -m "Add due date support to todos"
```

### Merging Branches
```bash
git checkout main
git merge feature-color-output
git merge feature-due-dates
```

### Tagging Releases
```bash
git tag -a v0.1.0 -m "Initial release with color and due date features"
```

### Pushing to GitHub
```bash
git remote add origin https://github.com/yourusername/todo_cli.git
git push -u origin main
```

### Pull & Fetch from Remote
```bash
git pull origin main
git fetch origin
```

### Git Status & Diff
```bash
git status
git diff
git diff --staged
```

### Git Logs & History
```bash
git log
git log --oneline --graph
```

### Deleting Branches
```bash
git branch -d feature-color-output
git branch -d feature-due-dates
```


