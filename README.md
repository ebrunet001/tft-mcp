# Teamfight Tactics MCP Server

> Connect AI assistants to TFT data via MCP — player profiles, ranked stats, match history, composition analysis, augment optimization, and AI-powered coaching.

[![Run on Apify](https://img.shields.io/badge/Run%20on-Apify-blue)](https://apify.com/scrapmania/teamfight-tactics-mcp-server---ai-game-analysis?fpr=ebrunet001)

## Features

- **10 MCP tools** for comprehensive TFT data access
- Player profiles — search players by Riot ID across all regions
- Ranked stats — tier, rank, LP, win/loss ratio
- Match history — recent matches with detailed statistics
- Composition analysis — identify the strongest comps and your best playstyles
- Augment optimization — discover which augments have the highest win rates
- Live game lookup — see what your opponents are building in real time
- AI-powered coaching — personalized advice tailored to your rank and playstyle
- Works with **Claude Desktop, Claude Code, ChatGPT** and any MCP-compatible client

## Quick Start

Connect to the MCP server using the Streamable HTTP endpoint:

```
https://scrapmania--teamfight-tactics-mcp-server---ai-game-analysis.apify.actor/mcp?token=YOUR_APIFY_TOKEN
```

1. [Get your free Apify API token](https://console.apify.com/account/integrations?fpr=ebrunet001)
2. Add the URL above as a custom MCP connector in your AI client
3. Start asking about any TFT player, match, or composition

### Claude Desktop Setup

Go to **Settings → MCP Servers → Add Custom Connector** and paste the URL above (replace `YOUR_APIFY_TOKEN` with your actual token).

### Claude Code Setup

Run `/permissions` and add `mcp__TFT__*` to the Allow list to permanently allow all TFT tools.

## Example Prompts

Once connected, your AI assistant can handle prompts like:

- *"What are the strongest comps in the current meta?"*
- *"Analyze my last 10 games — am I forcing comps too often?"*
- *"Which augments have the highest win rate for Reroll comps?"*
- *"Compare my TFT stats with a Challenger player"*
- *"I keep finishing 5th-8th. What am I doing wrong?"*

## Pricing

Pay-per-event — you only pay for the tools you actually use. The free tier gives you **$5 free credits every month**, enough for hundreds of tool calls.

## Links

- **Apify Store**: [Teamfight Tactics MCP Server](https://apify.com/scrapmania/teamfight-tactics-mcp-server---ai-game-analysis?fpr=ebrunet001)
- **Author**: [mrbridge on Apify](https://apify.com/mrbridge?fpr=ebrunet001)

## Related MCP Servers

- [League of Legends MCP Server](https://apify.com/scrapmania/lol-mcp-server?fpr=ebrunet001) — 13 tools for LoL player data, match history, and AI coaching
- [ESPN MCP Server](https://apify.com/scrapmania/espn-mcp-server?fpr=ebrunet001) — Live scores, standings, and stats across 25+ sports leagues
- [Todoist MCP Server](https://apify.com/scrapmania/todoist-ai-assistant?fpr=ebrunet001) — 35 tools for AI-powered task management

---

*Built by [mrbridge](https://apify.com/mrbridge?fpr=ebrunet001) — Usage must comply with Riot Games API Terms and Conditions.*
