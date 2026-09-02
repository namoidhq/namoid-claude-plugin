# NamoID Customer Identity for Claude Code

[![Validation](https://github.com/namoidhq/namoid-claude-plugin/actions/workflows/validate.yml/badge.svg)](https://github.com/namoidhq/namoid-claude-plugin/actions/workflows/validate.yml)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Official Claude Code marketplace repository for NamoID Customer Identity.

The plugin connects Claude Code to the canonical `https://mcp.namoid.in`
endpoint and uses NamoID's browser-based OAuth flow. It contains no credentials. Remote
permissions are revocable and use the protected-resource scopes
`customer-identity:read` and user-approved `customer-identity:configure`.

It includes six Customer Identity skills for setup, diagnosis, verification,
secure logout, session-security review, and production readiness. Claude Code
also receives a read-only session reviewer and a `/dryrun` command that previews
CLI setup without changing files or remote configuration.

## Install

```text
/plugin marketplace add namoidhq/namoid-claude-plugin
/plugin install customer-identity@namoid
```

## Security and contributions

The integration is open source under the [MIT License](LICENSE). See [CONTRIBUTING.md](CONTRIBUTING.md)
before proposing changes and [SECURITY.md](SECURITY.md) for private vulnerability
reporting. Never submit NamoID credentials, OAuth tokens, or customer data.

## Links

- [NamoID](https://namoid.in)
- [Documentation](https://docs.namoid.in)
- [Issues](https://github.com/namoidhq/namoid-claude-plugin/issues)
