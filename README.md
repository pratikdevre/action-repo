# Action Repo – Webhook Event Source

This is a basic GitHub repository created to test webhook events for the TechStaX Developer Assessment.

## Purpose
This repo is used to perform actions like:
- Pushing commits
- Creating pull requests
- Merging branches

Each of these actions triggers a GitHub webhook, which is connected to a Flask backend (in a separate repository). The backend listens to these events and stores them in a MongoDB database.

## How to Use
1. Clone this repo or make changes locally
2. Push changes to any branch (to trigger a `push` event)
3. Create a pull request from one branch to another


## Notes
- This repo doesn't contain any actual project code
- It's only meant to test GitHub webhook functionality
- The actual server logic is in the `webhook-repo`

---
