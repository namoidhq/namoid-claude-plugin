---
description: Preview NamoID Customer Identity setup without changing local files or remote configuration.
argument-hint: "[project-directory]"
allowed-tools: Bash(namoid *), Bash(npx namoid *)
---

Run the NamoID CLI from the requested project directory, or the current directory when none is provided:

1. `namoid detect --json`
2. `namoid doctor --json`
3. `namoid init --dry-run --json`

If `namoid` is not installed but the package is available to `npx`, use `npx namoid` for the same commands. Do not run non-dry-run initialization, edit files, create remote resources, or expose environment-variable values. Summarize the proposed actions and any blockers.
