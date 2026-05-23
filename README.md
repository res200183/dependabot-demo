cat > README.md << 'EOF'
# Dependabot DevSecOps Demo

## Project Overview

This project demonstrates a simple DevSecOps workflow using:

- GitHub Actions
- Dependabot
- Node.js
- CI/CD Pipeline
- Automated dependency updates
- Security vulnerability detection

---

## Features

### CI/CD Pipeline
GitHub Actions pipeline automatically:

- installs dependencies
- runs the Node.js application
- validates pull requests
- validates pushes to main branch

---

## Dependabot Integration

Dependabot automatically:

- scans npm dependencies
- scans GitHub Actions versions
- detects vulnerable packages
- creates automatic Pull Requests

---

## Technologies Used

- Node.js
- npm
- GitHub Actions
- Dependabot
- Git
- AWS EC2 (Amazon Linux 2023)

---

## Example Security Update

Dependabot detected a vulnerable lodash version:

- lodash 4.17.10

and automatically proposed upgrade to:

- lodash 4.18.1

---

## DevSecOps Concepts Practiced

- CI/CD automation
- Dependency management
- Automated security patching
- Pull Request validation
- GitHub Actions workflows
- Infrastructure access through SSH
- Git workflow

---

## Author

Created by res200183
EOF
