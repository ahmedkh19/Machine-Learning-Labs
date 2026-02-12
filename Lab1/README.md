<div align="center">

# Lab 1: Getting Started with Git and GitHub

**Version Control Fundamentals and Development Workflow**

[![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white)](https://git-scm.com)
[![GitHub](https://img.shields.io/badge/GitHub-Repository%20Hosting-181717?logo=github&logoColor=white)](https://github.com)
[![VS Code](https://img.shields.io/badge/VS%20Code-Editor-007ACC?logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](https://jupyter.org)

</div>

---

## Git vs GitHub

| | Git | GitHub |
|---|-----|--------|
| **What** | Version control system | Cloud platform built on Git |
| **Where** | Runs locally on your machine | Hosted on the web |
| **Purpose** | Track changes in files | Store, share, and collaborate on code |
| **Features** | Commits, branches, merges | Pull requests, issues, actions, pages |

---

## Core Concepts

| Concept | Description |
|:--------|:------------|
| **Repository** | A project folder tracked by Git |
| **Branch** | A parallel version of the repo for isolated work |
| **Commit** | A saved snapshot of changes with a descriptive message |
| **Pull Request** | A proposal to merge changes from one branch into another |
| **Merge** | Incorporating changes from one branch into another |

---

## Getting Files from GitHub

| Method | Command / Action | Use Case |
|:------:|------------------|----------|
| **Download** | Download ZIP from GitHub | Just want the files, no version control |
| **Clone** | `git clone <url>` | Full local copy with Git tracking |
| **Fork** | Fork button on GitHub | Your own copy of someone else's repo |

---

## Workflows

### Browser Workflow

```
Create Repo → Create Branch → Make Changes → Commit → Open PR → Merge → Delete Branch
```

| Step | Action |
|:----:|--------|
| 1 | Create a repository (with README) |
| 2 | Create a branch (e.g. `readme-edits`) |
| 3 | Make changes and commit them |
| 4 | Open a pull request |
| 5 | Review diffs, then merge |
| 6 | Delete the feature branch |

### GitHub Desktop Workflow

```
Install → Create Repo → Publish → Branch → Edit in VS Code → Commit → PR → Merge
```

| Step | Action |
|:----:|--------|
| 1 | Install GitHub Desktop and sign in |
| 2 | Create a local repository |
| 3 | Publish it to GitHub as a remote |
| 4 | Create a branch for changes |
| 5 | Edit files in VS Code, commit with a message |
| 6 | Publish branch and create a pull request |
| 7 | Merge PR, delete branch, fetch/pull origin to stay in sync |

---

## Jupyter Notebooks in VS Code

### Prerequisites

```
VS Code          Code editor
GitHub Desktop   Git GUI client
Anaconda         Python distribution & package manager
```

### Setup

| Step | Action |
|:----:|--------|
| 1 | Install the **Jupyter** and **Python** extensions in VS Code |
| 2 | Create a `.ipynb` file |
| 3 | Connect to a kernel (Python environment) |
| 4 | Write and run code cells |
| 5 | Commit the notebook via VS Code Source Control or GitHub Desktop |
