---
name : pr - description
description : Writes pull request descriptions. Use when creating a PR, or when user asks to summarize changes for pull request.
---

When writting a PR description:

1. run `git diff main...HEAD`  to see all changes to this branch
2. write a description follwing this format.

##What
Reorganize skill structure by moving pr-description skill to .github/skills/pr-description directory.

##Why 
This change centralizes all skill definitions in the .github/skills directory for better organization and maintainability. It follows a consistent directory structure where each skill has its own dedicated folder.

###changes
- Includes guidance on writing PR descriptions with a structured format (What/Why/Changes)
- Provides instructions for running `git diff main...HEAD` to review changes
- Defines the template format for consistent PR descriptions

