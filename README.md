# ost_lab_experiment-22.08.2025-

GitHub Environment Exploration – Experiments
A series of hands-on experiments to learn Git, GitHub, and collaboration workflows.

🔹 Experiment 1: Getting Started
Objective: Set up Git & GitHub basics.

Create a GitHub account

Install Git (git --version)

Configure username & email:

bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
🔹 Experiment 2: Repositories
Objective: Create and clone repos.

Create a new repo on GitHub (with README)

Clone locally:

bash
git clone https://github.com/username/repo.git


🔹 Experiment 3: File Operations
Objective: Manage files & commits.

Create a file (hello.txt)

Track & commit changes:

bash
git add hello.txt
git commit -m "Added hello.txt"
git push origin main


🔹 Experiment 4: Branching & Merging
Objective: Use branches for parallel development.

bash
git branch feature1
git checkout feature1
# make changes, commit
git checkout main
git merge feature1


🔹 Experiment 5: Pull Requests
Objective: Collaborate with PRs & reviews.

Push a branch to GitHub

Open a Pull Request

Add reviewers, discuss, and merge

🔹 Experiment 6: Forking & Contributions
Objective: Contribute to external repos.

Fork a repo & clone your fork

Make changes → Push → Open PR to original project

🔹 Experiment 7: Issues & Project Boards
Objective: Use GitHub for project management.

Create Issues (bugs/features)

Add labels & assignees

Organize tasks on a Project Board (Kanban)

🔹 Experiment 8: GitHub Actions (CI/CD)
Objective: Automate workflows.
Create .github/workflows/main.yml:

text
name: CI
on: [push]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - run: echo "Hello from GitHub Actions!"

🔹 Experiment 9: Documentation
Objective: Create project docs.

Enable Wiki

Add installation & usage pages

Link Wiki from README

🔹 Experiment 10: Security & Insights
Objective: Explore repo health & safety.

Enable branch protections (PR reviews required)

Check Dependency Graph & Dependabot alerts

Explore Insights → Traffic
