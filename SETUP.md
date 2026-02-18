# Setting up this documentation repo

This file describes how to turn this folder into a Git repo and connect it to GitBook. You can delete it after setup.

## 1. Initialize Git and make the first commit

From the `primmo-docs` folder:

```powershell
cd c:\Users\Nathan\code\primmo-docs
git init
git add .
git commit -m "Initial docs structure for GitBook"
```

## 2. Create the remote repository

- On GitHub (or your Git host), create a **new empty repository** (e.g. `primmo-docs` or `primmo-gitbook`).
- Do not add a README, .gitignore, or license there if you want to push this existing content.

Then add the remote and push:

```powershell
git remote add origin https://github.com/<org-or-user>/<repo-name>.git
git branch -M main
git push -u origin main
```

## 3. Connect GitBook to this repo

1. In [GitBook](https://www.gitbook.com/), create or open the space that should hold this documentation.
2. In the space header (top right), open **Configure** and choose **GitHub Sync**.
3. Authenticate with GitHub and install the GitBook app for the account/org that owns the repo.
4. Select this repository and the branch (e.g. `main`).
5. For the first sync, choose **GitHub → GitBook** to import the existing Markdown, or **GitBook → GitHub** if you prefer to start from an empty GitBook space and push its content into the repo.

After that, edits in GitBook (merged via change requests) are committed to the repo, and commits pushed to the repo are synced into GitBook.

## Optional: Add this folder to your Cursor workspace

To work on docs in the same Cursor window as your other Primmo projects, add the folder to your workspace (e.g. **File → Add Folder to Workspace** and select `primmo-docs`).
