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
