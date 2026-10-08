# Devin

**AI software engineer by Cognition**

Devin is an AI software engineer developed by Cognition for software development workflows.

It can work on software engineering tasks such as understanding repositories, writing and modifying code, debugging, testing, reviewing changes, and working on longer-running development tasks.

The Devin ecosystem includes **Devin Cloud, Devin CLI, DeepWiki, APIs, MCP integrations, GitHub workflows, and open source developer tools**.

This section collects official documentation, developer resources, open source repositories, CLI resources, APIs, integrations, and learning materials.

---

## Quick Navigation

* [About Devin](#about-devin)
* [Devin Cloud](#devin-cloud)
* [Devin CLI](#devin-cli)
* [Getting Started](#getting-started)
* [How Devin Works](#how-devin-works)
* [Software Engineering Tasks](#software-engineering-tasks)
* [Models](#models)
* [Sessions](#sessions)
* [GitHub](#github)
* [DeepWiki](#deepwiki)
* [MCP](#mcp)
* [API](#api)
* [QA & Testing](#qa--testing)
* [Terraform](#terraform)
* [Open Source](#open-source)
* [Useful Workflows](#useful-workflows)
* [Learning Path](#learning-path)
* [Official Resources](#official-resources)
* [Contributing](#contributing)
* [License](#license)

---

## About Devin

Devin is an AI software engineer developed by **Cognition**.

Unlike a traditional code completion tool, Devin is designed around completing broader software engineering tasks.

It can be used for:

* Code generation
* Debugging
* Refactoring
* Testing
* Code review
* Repository exploration
* Documentation
* Issue resolution
* Feature implementation
* Software maintenance
* Research
* Development automation

### Cognition

[Cognition](https://cognition.ai/)

### Devin

[Devin](https://devin.ai/)

### Documentation

[Devin Documentation](https://docs.devin.ai/)

### GitHub

[Cognition GitHub](https://github.com/CognitionAI)

---

## Devin Cloud

Devin Cloud provides an environment where software engineering tasks can be delegated to Devin.

A typical workflow can look like:

```text
Task
  ↓
Devin
  ↓
Understand repository
  ↓
Plan
  ↓
Implement
  ↓
Test
  ↓
Review
  ↓
Pull Request
```

This approach is useful for tasks that can be delegated and worked on asynchronously.

Possible tasks include:

* Implementing features
* Fixing bugs
* Updating dependencies
* Writing tests
* Investigating issues
* Reviewing code
* Updating documentation

### Devin

[Devin Cloud](https://devin.ai/)

---

## Devin CLI

**Devin CLI** brings Devin into the terminal.

It runs locally on the developer's machine and can work with the local repository, shell, tools, and development environment. It can also hand a task off to Devin Cloud when longer-running or asynchronous work is needed.

### Official CLI

[Devin CLI](https://devin.ai/cli)

### Installation

The current official installation command is:

```bash
curl -fsSL https://cli.devin.ai/install.sh | bash
```

Then start Devin:

```bash
devin
```

The CLI supports macOS, Linux, and Windows.

### Basic Usage

Start an interactive session:

```bash
devin
```

Start with an initial task:

```bash
devin -- fix the failing tests
```

Run Devin inside a project:

```bash
cd my-project
devin
```

### Local Development

Devin CLI can:

* Read local files
* Modify code
* Execute shell commands
* Work interactively
* Run development tasks
* Use MCP servers
* Use skills
* Use repository instructions

The local workflow is useful for exploration, prototyping, debugging, and interactive development.

---

## Getting Started

A practical way to start with Devin:

```text
1. Create or access a Devin account
          ↓
2. Connect your development environment
          ↓
3. Give Devin a software task
          ↓
4. Review its plan
          ↓
5. Let Devin work
          ↓
6. Inspect the changes
          ↓
7. Run tests
          ↓
8. Review the final result
```

For local development:

```text
Install Devin CLI
       ↓
Open repository
       ↓
Start Devin
       ↓
Give task
       ↓
Review changes
       ↓
Test
```

---

## How Devin Works

A simplified software engineering workflow looks like:

```text
User Request
     ↓
Understand Context
     ↓
Explore Repository
     ↓
Plan
     ↓
Implement
     ↓
Run Commands
     ↓
Test
     ↓
Review
     ↓
Deliver Result
```

The important distinction is that Devin is designed to work across multiple steps of a software engineering task instead of only generating isolated code snippets.

---

## Software Engineering Tasks

Devin can be useful for different stages of software development.

### Repository Exploration

Ask Devin to understand an unfamiliar codebase:

```text
Explain the architecture of this repository.
Identify the main entry points and important modules.
```

### Bug Fixing

```text
Investigate the failing tests and identify the root cause.
```

### Feature Development

```text
Implement the authentication feature described in this issue.
```

### Testing

```text
Add tests for the API endpoints and run the test suite.
```

### Refactoring

```text
Refactor this module while preserving its current behavior.
```

### Documentation

```text
Review the README and update it to match the current project.
```

### Code Review

```text
Review these changes for bugs, security issues, and maintainability.
```

---

## Models

The Devin ecosystem can work with multiple AI models.

Devin CLI currently exposes models from providers including:

* Anthropic
* OpenAI
* Google
* Cognition
* Open-weight models

The available model selection can change over time.

In Devin CLI, models can be selected from the session interface.

For current model availability, check:

[Devin CLI](https://devin.ai/cli)

---

## Sessions

A Devin session represents a software engineering task being worked on by the agent.

A session can involve:

* Repository exploration
* Planning
* Code changes
* Shell commands
* Testing
* Debugging
* Review
* Final delivery

A useful mental model is:

```text
Session
   │
   ├── Context
   ├── Repository
   ├── Instructions
   ├── Tools
   ├── Model
   ├── Changes
   └── Result
```

For longer tasks, Devin Cloud can continue working asynchronously.

---

## GitHub

GitHub is an important part of Devin-based development workflows.

Possible workflows include:

* Issues
* Pull requests
* Code review
* Repository maintenance
* Feature implementation
* Bug fixing
* Automated development tasks

A typical workflow can look like:

```text
GitHub Issue
     ↓
Devin
     ↓
Repository Analysis
     ↓
Implementation
     ↓
Tests
     ↓
Pull Request
     ↓
Human Review
     ↓
Merge
```

Devin can therefore be incorporated into existing Git-based development processes.

### Cognition GitHub

[Cognition GitHub Organization](https://github.com/CognitionAI)

---

## DeepWiki

**DeepWiki** is a Cognition project that generates documentation for public GitHub repositories.

It can help developers understand unfamiliar repositories by providing structured documentation and explanations.

### DeepWiki

[DeepWiki](https://deepwiki.com/)

### GitHub Repository

[DeepWiki GitHub](https://github.com/CognitionAI/deepwiki)

### DeepWiki MCP

DeepWiki also provides an MCP server with tools for:

* Asking questions
* Reading wiki structure
* Reading wiki contents

The current MCP endpoints are documented by the project.

---

## MCP

Devin supports the **Model Context Protocol (MCP)** for connecting AI agents to external tools and services.

MCP can provide access to:

* APIs
* Databases
* Documentation
* Development tools
* Internal services
* External systems

A simplified architecture:

```text
Devin
  │
  ├── Repository
  │
  ├── Terminal
  │
  ├── GitHub
  │
  └── MCP
       ├── APIs
       ├── Databases
       ├── Documentation
       └── External Tools
```

Devin CLI can use MCP servers as part of its local development workflow.

---

## API

Cognition provides APIs that allow Devin capabilities to be integrated into external workflows.

The API can be used to work programmatically with Devin functionality, including engineering sessions and organization-level resources.

Potential applications include:

* Automated task creation
* Engineering workflows
* Internal developer platforms
* CI/CD automation
* Issue processing
* Development operations

For API access and current capabilities:

[Devin Documentation](https://docs.devin.ai/)

---

## QA & Testing

Devin can also be used for software quality workflows.

Possible applications include:

* End-to-end testing
* Test generation
* Regression testing
* Bug investigation
* Test execution
* QA automation

Cognition maintains a public repository demonstrating Devin used for QA:

[QA-Devin](https://github.com/CognitionAI/qa-devin)

This makes Devin particularly interesting for exploring AI-assisted software testing and quality assurance.

---

## SWE-bench

Cognition also publishes Devin's SWE-bench results and methodology.

SWE-bench is a benchmark for evaluating AI systems on real-world software engineering tasks.

### Repository

[Devin SWE-bench Results](https://github.com/CognitionAI/devin-swebench-results)

This can be useful when studying:

* Coding agents
* Software engineering benchmarks
* Agent evaluation
* Automated issue resolution
* AI coding performance

---

## Terraform

Cognition maintains an official Terraform provider for Devin.

The provider allows organizations to manage Devin resources as infrastructure as code.

It currently supports resources including:

* Organizations
* Git permissions
* Playbooks
* Knowledge notes
* Secrets
* Schedules
* IP access lists
* Identity provider mappings

The provider uses the Devin v3 API.

### Repository

[Terraform Provider for Devin](https://github.com/CognitionAI/terraform-provider-devin)

### Example

```hcl
terraform {
  required_providers {
    devin = {
      source = "registry.terraform.io/cognitionai/devin"
    }
  }
}

provider "devin" {
}
```

Authentication can be provided through the appropriate Devin service-user credentials.

Do not commit API tokens or secrets to source control.

---

## Devin + Open Source

Devin can be useful when working with open source repositories.

A possible workflow:

```text
Find Repository
      ↓
Explore Codebase
      ↓
Understand Issue
      ↓
Create Plan
      ↓
Implement
      ↓
Run Tests
      ↓
Review Changes
      ↓
Create Pull Request
```

Potential use cases:

* First-time contributor assistance
* Issue investigation
* Documentation fixes
* Test generation
* Bug fixes
* Refactoring
* Dependency updates
* Pull request preparation

AI-assisted contribution should always include human review before changes are merged.

---

## Devin CLI + Open Source

The local CLI is especially useful when exploring an unfamiliar repository.

Example:

```bash
git clone https://github.com/example/project.git
cd project
devin
```

Then ask:

```text
Explain this repository and identify the best place to start contributing.
```

Or:

```text
Find an issue that looks suitable for a first contribution.
```

Or:

```text
Review this repository's contribution guidelines and explain how I can contribute.
```

---

## Useful Workflows

### Understand a Repository

```text
Analyze this repository.

Explain:
- architecture
- main components
- entry points
- testing strategy
- contribution workflow
```

### Investigate an Issue

```text
Analyze this GitHub issue and identify the likely root cause.
Do not modify the code yet.
```

### Plan Before Coding

```text
Create an implementation plan for this feature.
Identify affected files, dependencies, risks, and tests.
```

### Implement

```text
Implement the approved plan and run the relevant tests.
```

### Test

```text
Run the existing test suite.
Investigate and fix any failures caused by the changes.
```

### Review

```text
Review the final changes for:
- bugs
- security problems
- regressions
- maintainability
- missing tests
```

### Documentation

```text
Update the documentation to accurately describe the current implementation.
```

---

## Devin CLI Workflow

A practical local workflow:

```text
Open Repository
      ↓
devin
      ↓
Ask / Plan
      ↓
Implement
      ↓
Run Tests
      ↓
Review Diff
      ↓
Commit
      ↓
Push
```

The CLI also supports handing work off to Devin Cloud:

```text
Local Devin CLI
      ↓
/handoff
      ↓
Devin Cloud
      ↓
Continue working
```

This allows local interactive work and cloud-based autonomous work to complement each other.

---

## Open Source Projects from Cognition

Cognition publishes several open source projects and developer tools.

### Devin CLI

[Devin CLI](https://github.com/CognitionAI/devin-cli)

Devin's terminal-based coding agent.

### DeepWiki

[DeepWiki](https://github.com/CognitionAI/deepwiki)

Devin-generated documentation for public repositories.

### QA-Devin

[QA-Devin](https://github.com/CognitionAI/qa-devin)

An open source project focused on Devin performing QA tasks.

### SWE-bench Results

[Devin SWE-bench Results](https://github.com/CognitionAI/devin-swebench-results)

Results and methodology related to Devin's SWE-bench evaluation.

### Terraform Provider

[Terraform Provider for Devin](https://github.com/CognitionAI/terraform-provider-devin)

Terraform provider for managing Devin resources through infrastructure as code.

### Cognition GitHub

[CognitionAI](https://github.com/CognitionAI)

Explore all current public repositories.

---

## Learning Path

A practical path for learning Devin:

```text
1. Understand AI coding agents
             ↓
2. Explore Devin
             ↓
3. Learn Devin Cloud
             ↓
4. Install Devin CLI
             ↓
5. Work with a local repository
             ↓
6. Explore sessions
             ↓
7. Work with GitHub
             ↓
8. Explore DeepWiki
             ↓
9. Learn MCP
             ↓
10. Explore the API
             ↓
11. Explore QA workflows
             ↓
12. Explore Terraform
             ↓
13. Build real workflows
```

### Beginner

Start with:

* [Devin](https://devin.ai/)
* [Documentation](https://docs.devin.ai/)
* Devin Cloud
* Basic software engineering tasks
* Devin CLI

### Intermediate

Explore:

* GitHub workflows
* DeepWiki
* MCP
* Local development
* Testing
* Code review

### Advanced

Explore:

* Devin API
* Automated engineering workflows
* QA automation
* Terraform
* Organization management
* Infrastructure as code
* Agentic development workflows

---

## Projects

This section can be used to document experiments and projects built with Devin.

Each project can include:

* Project description
* Goal
* Repository
* Task
* Prompt
* Model
* Tools
* MCP integrations
* Results
* Tests
* Lessons learned

Example:

```text
projects/
└── project-name/
    ├── README.md
    ├── prompts/
    ├── results/
    └── tests/
```

---

## Official Resources

| Resource           | Link                                                                                            |
| ------------------ | ----------------------------------------------------------------------------------------------- |
| Devin              | [devin.ai](https://devin.ai/)                                                                   |
| Cognition          | [cognition.ai](https://cognition.ai/)                                                           |
| Documentation      | [Devin Docs](https://docs.devin.ai/)                                                            |
| Devin CLI          | [Devin CLI](https://devin.ai/cli)                                                               |
| GitHub             | [CognitionAI](https://github.com/CognitionAI)                                                   |
| DeepWiki           | [deepwiki.com](https://deepwiki.com/)                                                           |
| DeepWiki GitHub    | [CognitionAI/deepwiki](https://github.com/CognitionAI/deepwiki)                                 |
| Devin CLI GitHub   | [CognitionAI/devin-cli](https://github.com/CognitionAI/devin-cli)                               |
| QA-Devin           | [CognitionAI/qa-devin](https://github.com/CognitionAI/qa-devin)                                 |
| SWE-bench Results  | [CognitionAI/devin-swebench-results](https://github.com/CognitionAI/devin-swebench-results)     |
| Terraform Provider | [CognitionAI/terraform-provider-devin](https://github.com/CognitionAI/terraform-provider-devin) |

---

## Contributing

Cognition maintains multiple public repositories related to Devin.

You can contribute to open source projects through:

* Code
* Documentation
* Tests
* Issues
* Bug reports
* Pull requests
* Examples
* Developer tools

For this toolkit, useful contributions include:

* Devin CLI experiments
* Agentic development workflows
* QA examples
* GitHub workflows
* MCP examples
* DeepWiki experiments
* API integrations
* Terraform examples
* Tutorials
* Documentation

Before contributing, check the contribution guidelines of the specific repository.

[Cognition GitHub](https://github.com/CognitionAI)

---

## License

Cognition's open source repositories may use different licenses.

Always check the license of the specific project before using, modifying, or redistributing its code.

For example, the official Terraform provider repository is licensed under Apache-2.0.

Check each repository for its current license:

[Cognition GitHub](https://github.com/CognitionAI)

The **Open Source Toolkit** repository itself is licensed under the MIT License.

---

### Explore · Experiment · Build · Share
