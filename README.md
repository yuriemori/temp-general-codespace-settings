# General Codespace Settings

A template repository that provides a ready-to-use GitHub Codespace with commonly needed developer tools and extensions pre-configured.

## Overview

Use this repository as a template to quickly spin up a Codespace with essential CLI tools and VS Code extensions already set up — no manual configuration required.

## What's Included

### Base Image

- **[Microsoft Universal Dev Container](https://github.com/devcontainers/images/tree/main/src/universal)** (`mcr.microsoft.com/devcontainers/universal:2`) — includes a wide range of languages and runtimes out of the box.

### Dev Container Features

| Feature | Description |
|---------|-------------|
| **Node.js** | Node.js runtime via [stu-bell/devcontainer-features/node](https://github.com/stu-bell/devcontainer-features) |
| **Azure CLI** | Azure command-line interface for managing Azure resources |
| **GitHub CLI (`gh`)** | GitHub's official CLI for interacting with repositories, issues, PRs, and more |
| **GitHub Copilot CLI** | AI-powered command-line assistant |

### VS Code Extensions

| Extension | Description |
|-----------|-------------|
| **GitHub Copilot** | AI pair programmer that suggests code completions |
| **GitHub Copilot Chat** | Conversational AI assistant integrated into VS Code |
| **OpenAI Codex Agent** | OpenAI Codex agent for autonomous coding tasks in VS Code |

### VS Code Settings

- **Claude Agent** enabled for using claude agent in GitHub Copilot.

## Usage

1. Click **"Use this template"** to create a new repository from this template.
2. Open the new repository in GitHub Codespaces.
3. The Codespace will automatically build with all tools and extensions ready to use.

## License

See [LICENSE](LICENSE) for details.
