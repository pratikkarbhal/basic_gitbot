Random github-repo commits...
Logging bot activity in activity.txt


# 🔄 Random GitHub Activity

This is a GitHub Actions workflow that helps keep your GitHub profile active by making random commits.

## 📌 What It Does

- Runs every day at 6 AM UTC
- Picks a random number from 0 to 9
- If the number is between 0 to 2, it makes a commit to activity.txt in repo

## ⚙️ Setup

1. Create a **Personal Access Token (PAT)** with `repo` access.
2. Go to your repo → **Settings** → **Secrets and variables** → **Actions** → **New repository secret**.
3. Name the secret `PAT` and paste your token.

