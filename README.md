# Xenora AI Documentation

Source for the [Xenora AI](https://xenora.ai) product documentation, published with [Mintlify](https://mintlify.com).

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

From the repository root (where `docs.json` lives), start the local preview:

```bash
mint dev
```

The site will be available at `http://localhost:3000`.

## Project layout

```
.
├── docs.json              # Site configuration and navigation
├── index.mdx              # Introduction
├── quickstart.mdx         # Getting started
├── dashboard.mdx          # Dashboard overview
├── faq.md                 # Frequently asked questions
├── features/              # Working with cases
│   ├── kb.mdx             # Workspace, cases, document review
│   └── custom.mdx         # Custom workflows
├── settings/              # Account and admin settings
│   ├── general-settings.mdx
│   ├── teams.mdx
│   └── billing.mdx
├── doc-images/            # Screenshots referenced from pages
├── images/                # Brand and marketing imagery
└── logo/                  # Light and dark logos
```

## Publishing

Changes pushed to `main` are deployed automatically via the Mintlify GitHub app. Verify the preview locally with `mint dev` before opening a PR.

## Troubleshooting

- Dev server won't start: run `mint update` to pull the latest CLI.
- A page returns 404: confirm the path is listed in `docs.json` navigation and that you are running `mint dev` from the directory containing `docs.json`.

## Support

- Product support: [support@xenora.ai](mailto:support@xenora.ai)
- Mintlify reference: [mintlify.com/docs](https://mintlify.com/docs)
