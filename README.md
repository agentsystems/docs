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

### Phase 1: Core Documentation (17 pages)

The documentation is organized into sections that guide users from installation through agent development:

```
docs/
├── 🚀 Getting Started (4 pages)
│   ├── index.mdx                 # Welcome to AgentSystems
│   ├── installation.mdx           # System Requirements & Setup
│   ├── quickstart.mdx             # 5-Minute Quick Start
│   └── architecture.mdx           # How Components Work Together
│
├── ⚙️ Configuration (5 pages) - Critical for using agents beyond hello-world
│   ├── index.mdx                  # Configuration Overview & Dependency Chain
│   ├── credentials.mdx            # Step 1: API Keys & Environment Variables
│   ├── model-connections.mdx      # Step 2: AI Provider Connections
│   ├── registry-connections.mdx   # Step 3: Container Registries
│   └── agents.mdx                 # Step 4: Agent Deployment
│
├── 📖 User Guide (5 pages)
│   ├── cli-commands.mdx           # SDK Command Reference
│   ├── running-agents.mdx         # Execute Agents Step-by-Step
│   ├── working-with-files.mdx     # Artifacts & File I/O
│   ├── audit-logs.mdx             # Cryptographic Audit Trail
│   └── agent-hub.mdx              # Finding & Installing Agents
│
└── 🛠️ Build Agents (3 pages)
    ├── quickstart.mdx             # Your First Agent in 10 Minutes
    ├── agent-contract.mdx         # Required Endpoints (/invoke, /health)
    └── using-toolkit.mdx          # Model Access & Progress Tracking
```

**Phase 1 Total: 17 essential pages** covering everything users need to get started, configure, and build agents.

### Future Phases

Additional documentation will be added as the platform matures:
- API Reference with OpenAPI specifications
- Advanced topics (authentication, UI customization)
- Additional examples and tutorials
- Platform administration guides
- Troubleshooting and debugging

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
