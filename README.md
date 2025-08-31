# GitHub Collaborators Reader

A simple Bash script to list users with **read access** (pull permissions) for a GitHub repository.

---

## Author

**Ayoub**  
Date: 25/08/2025

---

## Description

This script integrates with the GitHub API to retrieve the collaborators of a repository and prints those who have **pull access**.  

It requires a GitHub username and personal access token for authentication, which should be exported as environment variables.

---

## Requirements

- Bash
- `curl`
- `jq` (for parsing JSON responses)

---

## Setup

1. Export your GitHub credentials:

```bash
export USERNAME="your_github_username"
export TOKEN="your_personal_access_token"
