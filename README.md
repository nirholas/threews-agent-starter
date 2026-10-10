# Your first three.ws agent

<!-- three.ws:badges -->
[![GitHub stars](https://img.shields.io/github/stars/nirholas/threews-agent-starter?style=flat&logo=github)](https://github.com/nirholas/threews-agent-starter/stargazers) [![License](https://img.shields.io/github/license/nirholas/threews-agent-starter?style=flat)](https://github.com/nirholas/threews-agent-starter/blob/HEAD/LICENSE) [![Last commit](https://img.shields.io/github/last-commit/nirholas/threews-agent-starter?style=flat)](https://github.com/nirholas/threews-agent-starter/commits) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat)](https://github.com/nirholas/threews-agent-starter/pulls) [![AI agent friendly](https://img.shields.io/badge/AI%20agents-AGENTS.md%20%2B%20llms.txt-6d5dfc?style=flat)](https://github.com/nirholas/threews-agent-starter/blob/HEAD/AGENTS.md)
<!-- /three.ws:badges -->


A one-click starting point for putting a live, animated 3D agent on a web page. Open the
repository in GitHub Codespaces and the demo starts automatically.

## Start in Codespaces

Use **Code > Codespaces > Create codespace on main**. When the forwarded port opens, the page
shows a real `<agent-3d>` component using the production three.ws CDN.

For a local checkout:

```bash
npm ci
npm run dev
```

Open <http://localhost:4173>.

## Make the character yours

Run this in the terminal:

```bash
npm create @three-ws/agent "a friendly robot guide"
```

The command uses the public generation lane, downloads the finished GLB, and creates a working
page. No three.ws account or API key is required. Replace the `body` URL in `index.html` with
the generated model URL or a path to the downloaded `agent.glb`.

## The whole integration

```html
<script type="module" src="https://three.ws/agent-3d/latest/agent-3d.js"></script>
<agent-3d body="https://three.ws/avatars/default.glb" name="Nova"></agent-3d>
```

`app.js` adds two real interactions: it finds a wave in the live animation catalog and calls
`playClip()`, and it calls `speak()` for a talking gesture.

## Verify

```bash
npm test
```

Continue with [LEARN.md](./LEARN.md), then explore the
[web component API](https://three.ws/docs/web-component) and the
[visual creator](https://three.ws/create).

## License

Apache-2.0

<!-- three.ws:growth -->
## Support the project

If threews-agent-starter saves you time, **[star it on GitHub](https://github.com/nirholas/threews-agent-starter)**. Stars are how other developers and AI agents find the repositories worth trusting, and they cost you one click.

Know someone who would use it? [Post on X](https://twitter.com/intent/tweet?text=threews-agent-starter%3A%20Live%203D%20AI%20agent%20in%20one%20page&url=https%3A%2F%2Fgithub.com%2Fnirholas%2Fthreews-agent-starter) · [Share on Bluesky](https://bsky.app/intent/compose?text=threews-agent-starter%3A%20Live%203D%20AI%20agent%20in%20one%20page%20https%3A%2F%2Fgithub.com%2Fnirholas%2Fthreews-agent-starter) · [Share on LinkedIn](https://www.linkedin.com/sharing/share-offsite/?url=https%3A%2F%2Fgithub.com%2Fnirholas%2Fthreews-agent-starter) · [Submit to Hacker News](https://news.ycombinator.com/submitlink?u=https%3A%2F%2Fgithub.com%2Fnirholas%2Fthreews-agent-starter&t=threews-agent-starter%3A%20Live%203D%20AI%20agent%20in%20one%20page) · [Share on Reddit](https://www.reddit.com/submit?url=https%3A%2F%2Fgithub.com%2Fnirholas%2Fthreews-agent-starter&title=threews-agent-starter%3A%20Live%203D%20AI%20agent%20in%20one%20page)

## Built for AI agents too

Coding agents and LLM tooling can read this repo directly: [AGENTS.md](./AGENTS.md), [llms.txt](./llms.txt), [llms-full.txt](./llms-full.txt). Point an agent at `https://github.com/nirholas/threews-agent-starter` and it has the context it needs.

## More from the same author

- [All repositories by nirholas](https://github.com/nirholas/nirholas#readme): the full catalog, grouped by topic
- [three.ws](https://three.ws): the platform for 3D AI agents with Solana wallets, a skill marketplace and x402 payments
- Questions or ideas: [open an issue](https://github.com/nirholas/threews-agent-starter/issues) or [start a discussion](https://github.com/nirholas/threews-agent-starter/discussions)

## Contributors

[![Contributors](https://contrib.rocks/image?repo=nirholas/threews-agent-starter)](https://github.com/nirholas/threews-agent-starter/graphs/contributors)

## Star history

[![Star History Chart](https://api.star-history.com/svg?repos=nirholas/threews-agent-starter&type=Date)](https://www.star-history.com/#nirholas/threews-agent-starter&Date)

<!-- /three.ws:growth -->
