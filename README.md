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
