# Lab 1 - Getting Started with Git and GitHub

## Topics Covered

### Git vs GitHub
- **Git** - A version control system that tracks changes in files
- **GitHub** - A cloud platform built around Git for storing, sharing, and collaborating on code
- Git handles versioning locally; GitHub hosts it remotely and adds collaboration features (pull requests, issues, etc.)

### Core Concepts
| Term | Meaning |
|------|---------|
| **Repository** | A project folder tracked by Git |
| **Branch** | A parallel version of the repo for isolated work |
| **Commit** | A saved snapshot of changes with a message |
| **Pull Request** | A proposal to merge changes from one branch into another |
| **Merge** | Incorporating changes from one branch into another |

### Getting Files from GitHub
| Method | When to Use |
|--------|-------------|
| **Download** | Just want the files, no version control |
| **Clone** | Want a full local copy with Git tracking |
| **Fork** | Want your own copy of someone else's repo on GitHub |

### GitHub Workflow (Browser)
1. Create a repository (with README)
2. Create a branch (e.g. `readme-edits`)
3. Make changes and commit them
4. Open a pull request
5. Review diffs, then merge
6. Delete the feature branch

### GitHub Desktop Workflow
1. Install GitHub Desktop and sign in
2. Create a local repository
3. Publish it to GitHub as a remote
4. Create a branch for changes
5. Edit files in VS Code, commit with a message
6. Publish branch and create a pull request
7. Merge PR, delete branch, fetch/pull origin to stay in sync

### Jupyter Notebooks in VS Code
- **Prerequisites**: VS Code, GitHub Desktop, Anaconda
- Install the **Jupyter** and **Python** extensions in VS Code
- Create a `.ipynb` file, connect to a kernel (Python environment)
- Write and run code cells
- Commit the notebook to GitHub via VS Code Source Control or GitHub Desktop
