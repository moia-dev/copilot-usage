# Copilot Usage Report


## Getting Started

1. [Create repository]([https://github.com/new?template_name=copilot-usage-template&template_owner=austenstone](https://github.com/new?template_name=copilot-usage-template&template_owner=austenstone&name=copilot-usage-report&description=Generates%20usage%20reports%20for%20GitHub%20Copilot))
2. [Create secret](../../settings/secrets/actions/new)
   - Name: TOKEN
   - Secret: [Create PAT(Personal Access Token)](https://github.com/settings/tokens/new?scopes=admin:org) (consider expiration date)
3. [Run workflow](../../actions/workflows/copilot-usage.yml)

## Viewing Report

This will run every night and produce a report. View the reports [here](../../actions/workflows/copilot-usage.yml).
