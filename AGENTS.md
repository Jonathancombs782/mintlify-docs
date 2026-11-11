> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- "Program" for on-chain programs (not "smart contract" as the primary term)
- "Account" for Solana accounts; "wallet" only for keypair/wallet tooling
- "Cluster" for Devnet / Testnet / Mainnet Beta; "network" only in general prose
- "Validator" for validator operators; "RPC node" for API-serving nodes
- Use "SOL" for the token and "lamport" for the smallest unit

## Style preferences

Follow the existing pages: short imperative steps, Solana CLI commands in code blocks with sample output, and version numbers only when verified against a current release.

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document only what is in this repo's Solana docs snapshot (CLI, clusters, concepts, RPC, validators, Geyser plugins).
- Do not add new product docs for other projects here; this repo is a Solana documentation copy.
- Do not invent API endpoints or CLI versions — verify against the Solana CLI / RPC reference first.
