# ALY6980 Capstone Project

Short description

This repository contains the source code and resources for the ALY6980 Capstone project. The project was cloned from an upstream template and organized into the `ALY6980` folder in this repository.

## Contents
- `ALY6980/` — main project source and assets (moved into this folder)

## Requirements
- Git (https://git-scm.com/)
- Any language/runtime specific to the project (see files under `ALY6980/`)

## Setup (local)
1. Clone the repository (if you haven't already):

```powershell
git clone https://github.com/PavanPratapReddy/ALY6980_Capstone.git
cd ALY6980_Capstone/ALY6980
```

2. Inspect project files and follow any language-specific setup instructions inside the `ALY6980` folder (for example `requirements.txt`, `package.json`, or README files specific to subprojects).

## How this repo was prepared
- The upstream repository `aparey/capstone` was cloned, the project files were moved into an `ALY6980/` subfolder, and changes were committed on a branch named `add-ALY6980-folder` before pushing to this repository.

## How to push your local changes to GitHub
1. Configure your git identity (only required once per machine or per repo):

```powershell
git config user.name "Your Name"
git config user.email "your.email@example.com"
```

2. Add or update your GitHub remote (example remote name `github`):

```powershell
git remote add github https://github.com/PavanPratapReddy/ALY6980_Capstone.git
# or update existing remote:
git remote set-url github https://github.com/PavanPratapReddy/ALY6980_Capstone.git
```

3. Push all branches and tags to your GitHub remote:

```powershell
git push github --all
git push github --tags
```

If the remote rejects the push because it contains commits you don't have locally, fetch and integrate remote changes before pushing:

```powershell
git fetch github main
git rebase github/main    # or: git merge github/main
git push github add-ALY6980-folder:main
```

If you need the repository to be replaced entirely (destructive), use `--force` carefully:

```powershell
git push --force github add-ALY6980-folder:main
```

## Next steps
- Review the files under `ALY6980/` and run any project-specific setup commands.
- If you want, I can commit and push this README for you — tell me if you want me to run those commands.

## License
Check the upstream project for license information or add your own LICENSE file.

---
Created/updated by project maintainer.

