# Copilot Usage Report

## Getting Started

1. [Create repository](https://github.com/new?template_name=copilot-usage-template&template_owner=austenstone&name=copilot-usage-report&description=Generates%20usage%20reports%20for%20GitHub%20Copilot)
2. [Create secret](../../settings/secrets/actions/new)
   - Name: TOKEN
   - Secret: [Create PAT(Personal Access Token)](https://github.com/settings/tokens/new?scopes=admin:org&description=copilot-usage-report) (consider expiration date)
3. [Run workflow](../../actions/workflows/copilot-usage.yml)

https://github.com/user-attachments/assets/dbc8e799-7c9a-4a21-8eea-34fdcabbf2aa

## Viewing Report

This will run every night and produce a report. View the reports [here](../../actions/workflows/copilot-usage.yml).

## Links

* [Source repository](https://github.com/austenstone/copilot-usage)
* [Report an issue](https://github.com/austenstone/copilot-usage/issues/new?template=Blank+issue)
* [Options](https://github.com/austenstone/copilot-usage/blob/main/action.yml#L8-L52)
* [REST API](https://docs.github.com/en/rest/copilot/copilot-usage)
