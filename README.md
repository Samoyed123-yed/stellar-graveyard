# Stellar Graveyard (a Miragine War-inspired autobattler)

An experimental browser strategy game by Samoyed. Three factions, timed army purchases, persistent battlefield units, AI builds, and online matchmaking. Independent project; not affiliated with Miragine War.

## Download the complete game

**[Download the full archive](https://github.com/Samoyed123-yed/stellar-graveyard/releases/latest/download/Stellar-Graveyard-Complete-Archive.zip)** from [Releases](https://github.com/Samoyed123-yed/stellar-graveyard/releases).

The complete ZIP contains all source code, the ready-to-play browser build, character sprites, covers, maps, music, original artwork, historical art versions, asset prompts, server code, tests and deployment examples. The repository is a lightweight download index; use the release ZIP rather than GitHub's automatically generated Source code ZIP.

## Quick start

Install **Node.js 24+**, extract the archive, and double-click **START_GAME.cmd** on Windows. On any platform run:

```sh
node tools/play-local.mjs
```

Open http://127.0.0.1:4173 for AI play. No dependency installation, GPT account, API key or original server is needed for this path.

For source development or local online matches:

```sh
npm install --global pnpm@10
pnpm install --frozen-lockfile
pnpm build
pnpm server
```

Open http://127.0.0.1:3000. The server creates a fresh local account database. Public hosting requires HTTPS; see the complete README inside the ZIP.

## AI-agent handoff

Give the extracted folder to your agent and ask it to read **AGENTS.md** and **README.md**. The game already runs as TypeScript/React/Vite/Node code; translation or framework conversion is unnecessary.

Current rules include five 10-second opening rounds, later 20-second rounds, three-second formation locks, a four-match concurrency limit and AI replacement after 65 seconds without a human opponent. Replacement AI uses generated nicknames; it is not a live human.

## Preservation notes

Experimental project, no longer actively developed. Source snapshot: fb3e769. Last production release: 1.0-20260914070704227-c2b2bb6. Archive prepared October 23, 2026. The old live site was unreachable at archive time.

Credentials, SSH keys, player account databases, caches, dependency folders, unrelated projects and private hosting metadata are excluded. The archive includes a file checksum manifest and a separate ZIP checksum.

No blanket license is granted for third-party music, logos, artwork or trademarks. Those assets are preserved as supplied; check rights before redistribution or commercial use. No separate open-source code license has been selected.
