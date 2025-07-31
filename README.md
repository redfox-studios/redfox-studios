# RedFox Studios - Website

This repository is for our website.

> [!TIP]
> **Branch Structure**
> - **Main** - Production release branch
> - **Beta** - Testing branch (merges to main when stable)  
> - **Dev** - Development branch (submit all PRs here please)

```mermaid
gitGraph
    commit id: "initial commit"
    branch beta
    branch dev
    checkout dev
    commit id: "feature-1"
    commit id: "feature-2"
    commit id: "feature-3"
    checkout beta
    merge dev id: "dev to beta"
    checkout dev
    commit id: "feature-4"
    checkout beta
    merge dev id: "dev to beta-2"
    checkout main
    merge beta id: "beta to main"
    checkout dev
    commit id: "and so on..."
```
