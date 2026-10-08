# OpenCode

**Open source AI coding agent**

OpenCode is an open source AI coding agent for working with codebases through AI-powered development workflows.

It can help developers understand repositories, plan changes, write and modify code, run commands, debug problems, review implementations, and automate development tasks.

This section collects the main OpenCode documentation, installation resources, CLI, models, agents, configuration, MCP, GitHub workflows, plugins, and learning resources.

---

## Quick Navigation

* [About OpenCode](#about-opencode)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [Basic Usage](#basic-usage)
* [CLI](#cli)
* [Models](#models)
* [Agents](#agents)
* [Configuration](#configuration)
* [Commands](#commands)
* [MCP](#mcp)
* [GitHub Integration](#github-integration)
* [Plugins](#plugins)
* [Permissions](#permissions)
* [Useful Workflows](#useful-workflows)
* [Open Source Workflows](#open-source-workflows)
* [Learning Resources](#learning-resources)
* [Learning Path](#learning-path)
* [Official Resources](#official-resources)
* [Contributing](#contributing)
* [License](#license)

---

## About OpenCode

OpenCode is an open source AI coding agent designed to work directly with software projects.

It can be used to:

* Understand existing code
* Explore unfamiliar repositories
* Generate code
* Modify files
* Debug problems
* Run development commands
* Write tests
* Review implementations
* Plan features
* Create specialized agents
* Connect external tools through MCP
* Automate development workflows

OpenCode supports different AI model providers, allowing developers to choose models according to their needs.

### Official Website

[OpenCode](https://opencode.ai)

### Documentation

[OpenCode Documentation](https://docs.opencode.ai/)

### Source Code

[OpenCode GitHub Repository](https://github.com/anomalyco/opencode)

---

## Getting Started

A simple OpenCode workflow looks like this:

```text
Install OpenCode
       ↓
Open a project
       ↓
Configure a model
       ↓
Start OpenCode
       ↓
Explore the codebase
       ↓
Plan changes
       ↓
Implement
       ↓
Test
       ↓
Review
```

Start with the official documentation:

[OpenCode Documentation](https://docs.opencode.ai/)

---

## Installation

OpenCode provides several installation methods depending on your operating system and preferred package manager.

Always check the official documentation for the latest installation instructions.

### Official Installation

[OpenCode Installation](https://opencode.ai)

### npm

```bash
npm install -g opencode-ai
```

### Homebrew

```bash
brew install opencode
```

### Windows

Windows users can use supported package managers and installation methods described in the official documentation.

[Installation Documentation](https://docs.opencode.ai/)

### Verify Installation

After installation:

```bash
opencode --version
```

---

## Basic Usage

Navigate to an existing project:

```bash
cd my-project
```

Start OpenCode:

```bash
opencode
```

OpenCode will start its interactive terminal interface.

### Start in a Specific Directory

```bash
opencode /path/to/project
```

### Run a Prompt

You can also run OpenCode with a specific task:

```bash
opencode run "Explain how this project works"
```

Example:

```bash
opencode run "Find the main entry point of this application"
```

### Continue a Session

```bash
opencode -c
```

or:

```bash
opencode --continue
```

---

## CLI

OpenCode provides a command-line interface for interactive and automated development workflows.

### Main Command

```bash
opencode
```

### Run

Execute a prompt directly:

```bash
opencode run "Explain this repository"
```

### Models

List available models:

```bash
opencode models
```

### Authentication

Manage provider authentication:

```bash
opencode auth
```

### Agents

Manage agents:

```bash
opencode agent
```

### MCP

Manage MCP servers:

```bash
opencode mcp
```

### Plugins

Manage plugins:

```bash
opencode plugin
```

### Upgrade

Update OpenCode:

```bash
opencode upgrade
```

For the complete CLI reference:

[OpenCode CLI Documentation](https://dev.opencode.ai/docs/cli/)

---

## Models

OpenCode can work with multiple AI model providers.

This makes it possible to choose models based on:

* Coding performance
* Reasoning
* Context size
* Speed
* Cost
* Availability
* Project requirements

### List Models

```bash
opencode models
```

You can refresh the model list:

```bash
opencode models --refresh
```

You can also filter by provider:

```bash
opencode models anthropic
```

### Model Format

Models are referenced using:

```text
provider/model
```

For example:

```text
provider/model-name
```

The exact providers and models available depend on the current OpenCode configuration.

### Specify a Model

```bash
opencode --model provider/model
```

Or with `run`:

```bash
opencode run --model provider/model "Review this code"
```

### Authentication

Provider authentication can be managed through:

```bash
opencode auth
```

Always follow the provider's current authentication requirements.

---

## Agents

Agents are specialized AI assistants designed for different development tasks.

OpenCode includes different agent modes and allows developers to create customized agents.

Common use cases include:

* Implementation
* Planning
* Code review
* Debugging
* Research
* Documentation
* Testing
* Specialized workflows

### Build

The Build workflow is intended for implementation tasks.

Example:

```bash
opencode run "Implement the missing function in src/"
```

### Plan

The Plan workflow can be used to analyze a project before making changes.

Example:

```bash
opencode run --agent plan "Analyze this repository and create an implementation plan"
```

### Create an Agent

OpenCode provides an agent command:

```bash
opencode agent create
```

Custom agents can define:

* Description
* Model
* Instructions
* Permissions
* Tools
* Specialized behavior

### Agent Directory

Project-level agents can be stored under:

```text
.opencode/agents/
```

Global agents can be stored under:

```text
~/.config/opencode/agents/
```

For more information:

[OpenCode Agents](https://docs.opencode.ai/docs/agents/)

---

## Configuration

OpenCode can be configured at the project or user level.

A project configuration can be stored as:

```text
opencode.json
```

or:

```text
opencode.jsonc
```

### Basic Configuration

```json
{
  "$schema": "https://opencode.ai/config.json"
}
```

### Project Structure

A project could look like:

```text
my-project/
├── opencode.json
├── src/
├── tests/
└── README.md
```

### Configuration Options

OpenCode configuration can define:

* Models
* Providers
* Agents
* Permissions
* Commands
* Plugins
* MCP servers
* Themes
* Keybindings
* Other project behavior

### Global Configuration

User-level configuration can be stored under:

```text
~/.config/opencode/
```

### Configuration Schema

```text
https://opencode.ai/config.json
```

More information:

[OpenCode Configuration](https://docs.opencode.ai/docs/config/)

---

## Commands

OpenCode supports custom commands for repetitive development workflows.

Commands can be stored inside:

```text
.opencode/commands/
```

A command can encapsulate a reusable prompt or development workflow.

Example structure:

```text
.opencode/
└── commands/
    ├── test.md
    ├── review.md
    └── documentation.md
```

This can help teams standardize common AI-assisted workflows.

---

## MCP

OpenCode supports the **Model Context Protocol (MCP)**.

MCP allows AI agents to connect to external tools and services.

Possible integrations include:

* APIs
* Databases
* Documentation
* Development tools
* External services
* Internal systems
* Data sources

### MCP Commands

List MCP servers:

```bash
opencode mcp list
```

Add an MCP server:

```bash
opencode mcp add
```

Authenticate an MCP server:

```bash
opencode mcp auth <name>
```

Debug an MCP server:

```bash
opencode mcp debug <name>
```

MCP configuration can also be managed through OpenCode configuration files.

---

## GitHub Integration

OpenCode can be integrated into GitHub-based development workflows.

Potential use cases include:

* Issue analysis
* Pull request assistance
* Code review
* Repository maintenance
* Automated development tasks
* CI workflows

OpenCode can also be used directly inside repositories while following normal Git workflows.

Example:

```text
Issue
  ↓
Understand repository
  ↓
Plan solution
  ↓
Implement
  ↓
Run tests
  ↓
Review changes
  ↓
Commit
  ↓
Pull Request
```

For the latest GitHub integration capabilities, consult the official documentation:

[OpenCode Documentation](https://docs.opencode.ai/)

---

## Plugins

OpenCode supports plugins for extending its functionality.

Plugins can provide additional integrations and capabilities.

Always review third-party plugins before installing them.

Before installing a plugin, consider:

* Source code
* Permissions
* Maintainer
* Dependencies
* Security implications
* Access to project files
* Access to credentials or external services

Official documentation:

[OpenCode Documentation](https://docs.opencode.ai/)

---

## Permissions

AI coding agents may interact with project files and development tools.

Permissions should therefore be configured carefully.

Depending on the workflow, you may want an agent to:

* Read files
* Edit files
* Create files
* Run commands
* Access external services

For example, a review-oriented workflow should have more restricted permissions than an implementation agent.

A good practice is:

```text
Read
 ↓
Analyze
 ↓
Plan
 ↓
Review permissions
 ↓
Modify
 ↓
Test
 ↓
Review
```

Never assume generated code is correct.

Always review important changes before committing or deploying them.

---

## Useful Workflows

### Understand a Repository

```bash
opencode run "Explain the architecture of this repository"
```

### Find a Bug

```bash
opencode run "Investigate the likely cause of the failing tests"
```

### Plan a Feature

```bash
opencode run --agent plan "Create a plan for adding authentication"
```

### Implement a Feature

```bash
opencode run "Implement the authentication feature described in the issue"
```

### Write Tests

```bash
opencode run "Add tests for the functions in src/"
```

### Review Code

```bash
opencode run "Review this implementation for bugs, security issues, and maintainability"
```

### Refactor

```bash
opencode run "Refactor this module without changing its public behavior"
```

### Documentation

```bash
opencode run "Improve the README based on the current project structure"
```

### Understand an Error

```bash
opencode run "Explain this error and identify possible solutions"
```

---

## Open Source Workflows

OpenCode can be useful when contributing to open source projects.

A practical workflow is:

```text
Find Issue
    ↓
Understand Repository
    ↓
Read Contribution Guidelines
    ↓
Create Plan
    ↓
Implement
    ↓
Run Tests
    ↓
Review Diff
    ↓
Commit
    ↓
Open Pull Request
```

Useful tasks include:

* Understanding unfamiliar codebases
* Fixing bugs
* Writing tests
* Improving documentation
* Refactoring
* Investigating issues
* Reviewing changes
* Preparing pull requests

AI should assist the contributor while the contributor remains responsible for the final changes.

---

## OpenCode + AI Models

One of the strengths of OpenCode is the ability to work with different models.

A workflow can look like:

```text
OpenCode
    ↓
Model Provider
    ↓
AI Model
    ↓
Agent
    ↓
Tools
    ↓
Project
```

This makes OpenCode useful for experimenting with different models and comparing their behavior in real development tasks.

---

## OpenCode + MCP

Combining OpenCode with MCP can extend an AI coding workflow beyond the local repository.

For example:

```text
OpenCode
    │
    ├── Local Files
    │
    ├── Terminal
    │
    ├── Git
    │
    └── MCP
          ├── Documentation
          ├── APIs
          ├── Databases
          └── External Tools
```

This makes MCP especially useful for building more capable development assistants.

---

## Learning Resources

### Official Website

[OpenCode](https://opencode.ai)

### Documentation

[OpenCode Documentation](https://docs.opencode.ai/)

### CLI

[CLI Documentation](https://dev.opencode.ai/docs/cli/)

### Configuration

[Configuration Documentation](https://docs.opencode.ai/docs/config/)

### Agents

[Agents Documentation](https://docs.opencode.ai/docs/agents/)

### GitHub

[OpenCode Repository](https://github.com/anomalyco/opencode)

---

## Learning Path

A practical path for learning OpenCode:

```text
1. Understand AI coding agents
            ↓
2. Install OpenCode
            ↓
3. Open a project
            ↓
4. Learn the CLI
            ↓
5. Explore models
            ↓
6. Use agents
            ↓
7. Configure permissions
            ↓
8. Create custom workflows
            ↓
9. Explore MCP
            ↓
10. Work with GitHub
            ↓
11. Build real projects
            ↓
12. Contribute to Open Source
```

### Beginner

Start with:

* OpenCode website
* Official documentation
* Installation
* Basic CLI usage
* Models
* Basic agents

### Intermediate

Explore:

* Configuration
* Custom agents
* Commands
* Permissions
* MCP
* GitHub workflows

### Advanced

Explore:

* Custom agents
* MCP integrations
* Automated workflows
* Plugins
* Multi-step development workflows
* Open source contribution workflows

---

## Projects

This section can be used to document experiments and projects built with OpenCode.

Each project can include:

* Project description
* Goal
* Repository
* Model used
* Agent configuration
* Commands
* MCP integrations
* Results
* Lessons learned

Example:

```text
projects/
└── project-name/
    ├── README.md
    ├── opencode.json
    └── .opencode/
        ├── agents/
        └── commands/
```

---

## Official Resources

| Resource            | Link                                                        |
| ------------------- | ----------------------------------------------------------- |
| OpenCode            | [opencode.ai](https://opencode.ai)                          |
| Documentation       | [OpenCode Docs](https://docs.opencode.ai/)                  |
| CLI                 | [CLI Docs](https://dev.opencode.ai/docs/cli/)               |
| Configuration       | [Config Docs](https://docs.opencode.ai/docs/config/)        |
| Agents              | [Agent Docs](https://docs.opencode.ai/docs/agents/)         |
| GitHub              | [anomalyco/opencode](https://github.com/anomalyco/opencode) |
| GitHub Organization | [Anomaly](https://github.com/anomalyco)                     |

---

## Contributing

OpenCode is an open source project and contributions are welcome.

You can contribute through:

* Code
* Documentation
* Tests
* Examples
* Bug reports
* Issues
* Pull requests
* Feature discussions
* Community support

For this toolkit, useful contributions include:

* OpenCode tutorials
* Agent examples
* MCP examples
* Configuration examples
* AI-assisted development workflows
* Open source experiments
* Documentation improvements

Before contributing to OpenCode itself, review the current project guidelines:

[OpenCode GitHub](https://github.com/anomalyco/opencode)

---

## License

OpenCode has its own project license and terms.

Check the current license directly in the official repository:

[OpenCode GitHub](https://github.com/anomalyco/opencode)

The **Open Source Toolkit** repository itself is licensed under the MIT License.

---

### Explore · Experiment · Build · Share
