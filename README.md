# GitHub Copilot Chat in Visual Studio Code

This repository is for providing feedback on the GitHub Copilot experience in VS Code, including both Copilot Chat and completions. You can use this repository to report issues or submit feature requests related to the user experience and interface of either extension.

- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) is an auto-complete style experience that provides inline code suggestions as you type, and may include experimental models for code completions.
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat) is a companion extension to GitHub Copilot that houses experimental chat features.

Learn more about [GitHub Copilot](https://github.com/features/copilot) in our [docs](https://code.visualstudio.com/docs/copilot/overview).

# Getting Started

## Install dependencies

```bash
npm install
```

## Run tests

```bash
npm test
```

# Providing Feedback

You can use this repository to file issues for Copilot Chat and completions in VS Code:

* Up-vote a feature or request a new one.
* Search for existing issues already reported for potential workarounds.
* Report a problem if you don't find what you are looking for.

# Project Structure
- package.json: Project metadata and dependencies
- test.js: Simple test script for CI
- .github/workflows/ci.yml: GitHub Actions workflow for CI
- docs/: Documentation and MCP config
- images/: Project images and GIFs

# Notes
- Always ensure all array fields in config files have at least one item to avoid CI errors.
- Use the provided test.js as a template for your own tests.
