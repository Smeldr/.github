# Smeldr

Smeldr is a ledger for the reasoning and decisions made by you and your AI agents. It keeps track of what was decided, why, who agreed, what is still in force, and what rests on it.

Not another place to store context. A record you can rely on, that people and agents both read and write.

**Decisions that stay put.** A Decision is proposed, then agreed by someone with the right to. Once agreed, it is never rewritten. If it changes, a new Decision replaces it, and the old one stays in the record.

**Rules where the work happens.** You say which files need whose approval. When a pull request touches them, Smeldr lists the Decisions that apply and puts the change in front of the right person or agent. In an Area that requires approval, a merge waits for the answer.

**Hand over what you choose.** Give an AI agent the right to approve changes in one Area, for as long as you say, and take it back whenever you like. Every answer is kept with who gave it, and the reason when there is one.

**A trail you can trust.** Every action records who did it and what kind of actor it was. Each reader sees only what they may read.

Self-hosted. Open source. The same tools for people and agents, over MCP.

## Start here

| Repository | What it is |
|---|---|
| [core](https://github.com/Smeldr/core) | The server and Go library |
| [mcp](https://github.com/Smeldr/mcp) | MCP server: the same tools for agents and people |
| [cli](https://github.com/Smeldr/cli) | Command line: search, history, grants, tokens, answering a check |
| [github](https://github.com/Smeldr/github) | GitHub App adapter for pull request checks (MIT) |

Modules: [media](https://github.com/Smeldr/media), [oauth](https://github.com/Smeldr/oauth), [agent](https://github.com/Smeldr/agent), [social](https://github.com/Smeldr/social).

[smeldr.dev](https://smeldr.dev) has the docs, the devlog and the stories. Licensed under AGPL v3 (core). The GitHub adapter is MIT.
