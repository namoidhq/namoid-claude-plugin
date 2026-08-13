# NamoID Setup Assistant for Claude Code

Official Claude Code marketplace repository for the NamoID Setup Assistant.

The plugin connects Claude Code to `https://api.namoid.in/v1/setup/mcp` and
uses NamoID's browser-based OAuth flow. It contains no credentials. Remote
permissions are revocable and limited to `setup.read` plus user-approved
`setup.write`.

## Install

```text
/plugin marketplace add namoidhq/namoid-claude-plugin
/plugin install namoid-setup-assistant@namoid
```

## Security and contributions

The integration is open source under Apache-2.0. See [CONTRIBUTING.md](CONTRIBUTING.md)
before proposing changes and [SECURITY.md](SECURITY.md) for private vulnerability
reporting. Never submit NamoID credentials, OAuth tokens, or customer data.
