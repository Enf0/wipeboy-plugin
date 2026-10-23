# Wipeboy for Claude, ChatGPT and Codex

The Wipeboy connector at https://wipeboy.enfo.dev/mcp and its raid-log-analysis skill, as a plugin for The Dragonfell Tribe (Kazzak-EU). With the skill,
the model reads raid logs the way the method says; a connector alone brings only the tools.

## Add it

In Claude (claude.ai or Claude Desktop): **Customize → Plugins → Add → Add marketplace**, enter `Enf0/wipeboy-plugin`, then add
the Wipeboy plugin and sign in with Warcraft Logs. With **Sync automatically** on, Claude keeps it up to date; the
marketplace's **Refresh** updates it at once.

In Claude Code: `/plugin marketplace add Enf0/wipeboy-plugin`, then `/plugin install wipeboy@wipeboy`.

In Codex, also Codex inside the ChatGPT desktop app: Plugins → **Add** → **Add plugin marketplace**, enter `Enf0/wipeboy-plugin`
(or `codex plugin marketplace add Enf0/wipeboy-plugin`), install Wipeboy, then sign in to its server under Plugins → **MCPs**. A
ChatGPT workspace admin can import it for the workspace: Admin Console → Plugins → Add → Import marketplace, with
`https://github.com/Enf0/wipeboy-plugin` as the source. ChatGPT's chats, on the web, a phone or the desktop app, don't run a
plugin's server: there add https://wipeboy.enfo.dev/mcp as a custom connector (the tools without the skill).

Made with [Wipebot](https://github.com/Enf0/wipebot): `wipebot plugin DIR` writes this repository.
