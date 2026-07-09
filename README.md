# poc-copilot-tracking

This repository is a proof of concept for tracking GitHub Copilot agent pull requests.

It demonstrates two pieces of automation:

- A pull request workflow that labels PRs opened by `github-copilot[bot]` and leaves a summary comment.
- A weekly report workflow that runs Copilot PR analysis and uploads the generated report as an artifact.

The intended end state is a small, visible POC repo for observing Copilot-driven PR activity over time.