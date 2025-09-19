# AgentSystems Documentation

Documentation for the AgentSystems platform - a system for running AI agents on your infrastructure.

This repository contains documentation for:

- Platform installation and setup
- Configuration guides (models, credentials, registries)
- Running and managing agents
- Building custom agents
- API reference

**[Visit the documentation](https://docs.agentsystems.ai)** *(in development)*

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Changes to the documentation are typically deployed via CI/CD when merged to the main branch.

## Documentation Structure

The documentation is organized into the following sections:

```
📚 Documentation
├── 🚀 Getting Started (5 pages)
│   ├── index.mdx - Welcome to AgentSystems
│   ├── quickstart.mdx - 5-Minute Quick Start
│   ├── concepts.mdx - Understanding AgentSystems
│   ├── installation.mdx - Installation & Setup
│   └── next-steps.mdx - What's Next?
│
├── ⚙️ Configuration (5 pages)
│   ├── index.mdx - Configuration Overview
│   ├── credentials.mdx - API Keys & Credentials
│   ├── models.mdx - AI Model Connections
│   ├── registries.mdx - Container Registries
│   └── agents.mdx - Agent Deployments
│
├── 📖 User Guide (11 pages)
│   ├── running-agents.mdx - Running Agents
│   ├── working-with-files.mdx - Files & Artifacts
│   ├── agent-hub.mdx - Agent Hub & Marketplace
│   ├── programmatic-access.mdx - CLI & API Usage
│   ├── monitoring/
│   │   ├── executions.mdx - Execution History
│   │   ├── audit-logs.mdx - Audit Trail
│   │   └── troubleshooting.mdx - Debugging Issues
│   ├── advanced/
│   │   ├── authentication.mdx - Bearer Tokens
│   │   └── ui-customization.mdx - Themes & UI Features
│   └── reference/
│       └── cli-commands.mdx - CLI Reference
│
├── 🛠️ Build Agents (11 pages)
│   ├── index.mdx - Building for AgentSystems
│   ├── quickstart.mdx - Your First Agent
│   ├── development/
│   │   ├── agent-contract.mdx - Required Endpoints
│   │   ├── local-development.mdx - Dev Environment
│   │   └── testing.mdx - Testing Your Agent
│   ├── capabilities/
│   │   ├── using-models.mdx - AI Model Access
│   │   ├── progress-tracking.mdx - Progress Updates
│   │   ├── file-handling.mdx - Processing Files
│   │   └── workflows.mdx - LangGraph & Multi-step
│   ├── distribution/
│   │   ├── packaging.mdx - Docker & Versioning
│   │   └── publishing.mdx - Share Your Agent
│   └── examples/
│       ├── hello-world.mdx - Minimal Agent
│       ├── file-processor.mdx - File Processing
│       └── production-agent.mdx - Production Example
│
└── 📋 API Reference (3-4 pages)
    ├── index.mdx - API Overview
    ├── gateway-api.mdx - Gateway Endpoints
    ├── agent-api.mdx - Agent Contract
    └── openapi.json - OpenAPI Specification
```

**Total: ~32 pages** organized for progressive learning and easy navigation.

## Contributing

We welcome contributions to improve the documentation! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [AgentSystems GitHub](https://github.com/agentsystems/agentsystems)
- [AgentSystems Discord](https://discord.gg/H26CEWfT)
- [Mintlify documentation](https://mintlify.com/docs)
