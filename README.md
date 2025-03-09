# GitHub Branchig Demo

I am learning git-branch-demo

## 1. Create the Repository and Clone it locally

> 1. Log in to GitHub and click the **New Repository** button.
> 1. Set the repository name, description, and choose **main** as the default branch.
> 1. Clone the new repository locally:

```powershell
    git clone <repo-url>
    cd <repo-folder>
```

## 2. Set Up the Main Branch

> 1. Ensure your local **main** branch is up to date:

```powershell
git checkout main
git pull origin main
```

## 3. Create and Set Up **swamy/feature1**

- **Create the Feature Branch from main:**

  ```sh
  git checkout -b swamy/feature1 main
  git push -u origin swamy/feature1
  ```
