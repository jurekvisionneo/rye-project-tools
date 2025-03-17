# Rye Project Tools 🐍🚀

Helper script to create and pull Python projects managed by Rye, with GitHub integration.

## Features

- 📁 Create new Rye-managed Python projects with GitHub repo creation.
- 🔌 Choose between SSH or HTTPS remotes.
- 🔐 Optionally create public or private repositories.
- 🏢 Supports creating repos under personal account or organization.
- 📄 Optionally use a GitHub template repo.
- 🚀 Pull existing projects, sync Rye environments, auto open in VS Code.

---

## Installation

1. Clone this repo:

```bash
git clone https://github.com/jurekvisionneo/rye-project-tools.git
```

2. Source the script:

```bash
echo "source ~/path/to/rye-project-tools/rye_project_tools.sh" >> ~/.zshrc
source ~/.zshrc
```

3. Usage:

```bash
nrp   # Create new project
prp   # Pull existing project
```

---

## Requirements:

- Rye installed
- GitHub CLI (`gh`) authenticated
- VS Code installed
