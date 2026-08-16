# GitHub Browser

Browse every GitHub repository you can reach — across all your personal accounts and organizations — from one place. It enumerates your orgs and repos over your own machine's git and gh credentials (run `pags up`), then answers questions about what exists: which repos are where, who owns them, when they were last touched, open issues and pull requests, branches and languages. Strictly read-only: it lists, searches and explains, and never pushes, opens, closes, comments or changes anything.

## AI billing

This generated agent does not use the ProAgentStore Cloudflare Workers AI binding by default. AI calls require caller-provided Cloudflare Workers AI credentials:

- `X-CF-Account-ID`
- `X-CF-AI-Token`

That makes inference spend bill to the caller's Cloudflare account, not the ProAgentStore platform account.

## Development

```bash
pnpm install
pnpm dev
```

## Deploy

```bash
pnpm deploy
```
