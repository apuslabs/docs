# APUS Network Documentation

Documentation for the APUS Network platform, enabling verifiable decentralized AI through deterministic GPU computing.

This repository contains the complete documentation for developers building on the APUS Network.

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

For APUS Network specific development, ensure you're connected to the correct AO network when testing integrations.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.
- For APUS Network integration issues, verify you're using the correct AO process IDs and HyperBEAM node connections.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)
- [APUS Network Developer Discord](https://discord.gg/NVqpWB2m8k)
- [APUS Network GitHub](https://github.com/apuslabs)
