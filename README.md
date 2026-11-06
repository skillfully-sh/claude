# Skillfully for Claude

Install the Skillfully plugin marketplace in Claude Code:

```bash
claude plugin marketplace add skillfully-sh/claude
claude plugin install skillfully@skillfully
```

Then ask Claude to show your available Skillfully skills. Claude opens browser authentication on first use.

Documentation: https://www.skillfully.sh/integrations/skillfully

## Version 1.1.0

Session-linked conversation recording and free-text author surveys use separate tools and the host Allow permission flow. [Usage, data sharing and update instructions](plugins/skillfully/README.md). These features depend on the connected server advertising the corresponding tools; the production MCP endpoint is unchanged.

To refresh an existing GitHub installation:

```bash
claude plugin marketplace update skillfully
claude plugin update skillfully@skillfully
```

Start a new session after updating.
