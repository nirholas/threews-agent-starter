# AGENTS.md

Guidance for AI coding agents working in this repository.

## What this is

`threews-agent-starter`: Live 3D AI agent in one page. A responsive, Codespaces-ready <agent-3d> starter with motion, speech, a keyless create command and a ten-minute learning path.

Primary language: CSS.

## Where to start

- [README.md](README.md) has install, usage and configuration.
- [llms.txt](llms.txt) is a machine-readable summary; [llms-full.txt](llms-full.txt) inlines the README.
- Part of [three.ws](https://three.ws), a platform for 3D AI agents with Solana wallets. Catalog of sibling repositories: https://github.com/nirholas/nirholas#readme

## Develop

```bash
npm install
npm test
```

Scripts:
- `npm run dev`: `serve . -l 4173 --no-clipboard`
- `npm run check`: `node scripts/check.mjs`
- `npm run test`: `npm run check`

## Conventions

- Match the style of the surrounding code before introducing a new pattern.
- Read-only by default. Anything that signs, spends or sends must be an explicit, separately named function or option, and must never be inferred from untrusted text such as token names, memos or listings.
- Never commit credentials. Configuration comes from environment variables documented in the README.
- Keep changes small and covered by a test next to the code they change.
- This project is licensed under Apache-2.0; contributions are accepted under the same terms.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Report vulnerabilities privately through [SECURITY.md](SECURITY.md).
