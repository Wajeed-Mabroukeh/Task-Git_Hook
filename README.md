# Git Hook Script for Removing Trailing Whitespace

This script is designed to automatically remove trailing whitespace from files that are staged for commit in your Git repository. This can help maintain a cleaner codebase and prevent unnecessary changes in version control.

## How It Works

- The script is executed every time you attempt to commit changes.
- It iterates through the staged files and checks for trailing whitespace.
- Any trailing whitespace found is removed before the commit is completed.

## Installation

1. Save the script in the `.git/hooks/pre-commit` directory of your repository.
2. Make sure to give it executable permissions:
   ```bash
   chmod +x .git/hooks/pre-commit
   ```

## Usage

No additional usage is required; the script runs automatically with each commit!