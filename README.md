# Personal - Commit Logger Automation

This repository demonstrates a GitHub Actions workflow that automatically records commit details whenever changes are pushed to the `main` branch.

## Project Overview

The workflow captures commit activity and updates a `log.txt` file with useful commit information such as time, author, and commit message. This project is useful for understanding basic CI/CD automation, GitHub Actions workflows, repository permissions, and automated commit tracking.

## Tech Stack

- GitHub Actions
- Git
- YAML
- Linux Shell Commands

## Features

- Automatically triggers on push to the `main` branch
- Checks out the repository using GitHub Actions
- Records commit timestamp, author, and commit message
- Updates `log.txt` automatically
- Commits and pushes the updated log file back to the repository
- Uses `[skip ci]` to avoid unnecessary workflow loops

## Repository Structure

```text
talent-cog/
├── .github/
│   └── workflows/
│       └── commit-log.yml
├── README.md
└── log.txt
