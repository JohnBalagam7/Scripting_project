# GitHub API Access Script

This Bash script interacts with the GitHub API to list users with read access to a repository.

## Prerequisites

- [jq](https://stedolan.github.io/jq/) - Command-line JSON processor
- GitHub Personal Access Token - Ensure you have a valid token with necessary permissions.

## Setup

1. Clone the repository.
2. Ensure you have `jq` installed.
3. Set environment variables for `USERNAME` and `TOKEN` in the script or pass them during execution.
4. Run the script with the repository owner and name as arguments: `./github_api_access.sh owner repo_name`.

## Usage

To list users with read access to a repository:
