# Wipeboy is now Wipebot

Wipeboy was The Dragonfell Tribe's own copy of [Wipebot](https://wipebot.enfo.dev). It was retired on 9 November 2026,
and this plugin now uses the Wipebot connector, which serves any guild. New installs should add
[Enf0/wipebot-plugin](https://github.com/Enf0/wipebot-plugin) instead.

World of Warcraft raid analysis from Warcraft Logs reports. Ask why a pull wiped, how a raid night went, what keeps
wiping the raid, or how a player did and why their damage or healing is low, and get an answer the way an experienced
raid leader reads the log.

The plugin has two parts:

- **The connector** at https://wipebot.enfo.dev/mcp. Its tools read reports from Warcraft Logs and the game's guides,
  compute the facts in code and return them. You sign in with your Warcraft Logs account: once more after this
  update, since the new address is a new sign-in. What it sends to the server is what you ask the tools: report
  codes, bosses, pulls and character names.
- **The raid-log-analysis skill**: how to turn those facts into an answer, such as reading a boss's mechanics before
  judging them and never blaming the deaths after a wipe was decided.
