# Problem & Solution #2:
## problem::

The problem is based on how to push codes into github from code editor...

## Solution::
```bash
git init
git add README.md
git commit -m "first-commit"
git branch -M main
git remote add origin https://github.com/username/repo-name.git
git push -u origin main
```
--before using it, you must give ssh code in your github account.
process:: settings->Access->SSH and GPG keys-> New SSH key.

follow github's instruction for the process to install SSH keys in gitBash and gitHub..

## link::
```bash
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?tool=webui
```
->GitHub CLI for computer
->Web browser for GitHub