<div align="center">

# AugurScope

### Your ad data, in any AI.

**A local, read-only [MCP](https://modelcontextprotocol.io) server that connects your Google Ads, GA4, Microsoft Advertising, Meta and TikTok accounts to Claude, ChatGPT, Cursor and any MCP client — so you can ask about your campaigns in plain English.**

[![Website](https://img.shields.io/badge/website-augurscope.com-4f46e5)](https://augurscope.com)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0ea5e9)](https://augurscope.com/download)
[![Price](https://img.shields.io/badge/price-%2479%20one--time-059669)](https://augurscope.com/#pricing)
[![License](https://img.shields.io/badge/license-proprietary-lightgrey)](./LICENSE)

[**Get AugurScope →**](https://augurscope.com) · [How it works](https://augurscope.com/#how) · [Pricing](https://augurscope.com/#pricing) · [Support](https://augurscope.com/support)

<img src="https://augurscope.com/ads-mcp-demo-poster.jpg" alt="Asking AugurScope about wasted ad spend inside Claude" width="760">

</div>

---

> **Note:** This is the public documentation for AugurScope, a commercial, closed-source product. The application's source code is **not** included here. To install AugurScope, download it from [augurscope.com](https://augurscope.com).

## What is AugurScope?

Marketers now live inside AI assistants like Claude, ChatGPT and Cursor — but their advertising data doesn't. Getting campaign performance out of Google Ads, Meta, Microsoft, GA4 or TikTok still means wrestling with clunky dashboards, brittle CSV exports, or paying $100+/month for a connector that pipes your data through someone else's servers.

**AugurScope** is a Windows desktop app and local MCP server that gives any MCP-compatible AI client **read-only** access to your own ad and analytics accounts. You ask questions in plain English; the answers come straight from your live accounts. Your tokens never leave your machine.

```
You:    Which Google Ads campaigns wasted the most budget last month?
Claude: Pulling your Google Ads data… 3 campaigns spent $8,410 at a ROAS under 1.0 👇
        • Brand (Broad)      $3,920   0.7×
        • Competitor terms   $2,740   0.4×
        • DSA (Catch-all)    $1,750   0.9×
```

## Supported channels

| Channel | What you can ask about |
|---|---|
| **Google Ads** | Campaigns, ad groups, keywords, spend, conversions, search terms, Quality Score, MCC roll-ups |
| **Google Analytics 4 (GA4)** | Sessions, conversions, channels, source/medium, landing pages, funnels |
| **Microsoft Advertising (Bing)** | Campaigns, keywords, spend, conversions, side-by-side vs Google |
| **Meta Ads (Facebook & Instagram)** | Campaigns, ad sets, creatives, ROAS, CPA, placement breakdowns |
| **TikTok Ads** | Campaigns, ad groups, videos, spend, CPA, ROAS, completion rate |

## Works with your AI client

Claude Desktop · Claude Code · **ChatGPT** · Cursor · Windsurf · Cline — anything that speaks MCP.

## Why AugurScope

- 🔒 **100% local.** It runs on your machine and talks directly to each platform. Your data and tokens never touch our servers.
- 👁️ **Read-only by design.** It can analyse everything and change nothing — safe to point at a live account. It can never pause a campaign or edit a bid.
- ♾️ **Pay once.** One-time **$79**, no subscription, lifetime updates. One licence covers 3 computers.
- 🔌 **No lock-in.** Bring your own developer tokens and use whatever MCP client you like.

## How it works

1. **Install** — unzip and run on Windows. No dependencies, no Python, nothing to configure.
2. **Connect your accounts** — sign in to each platform through its normal screen. Your tokens are encrypted and stored on your machine.
3. **Add it to your AI** — one click for detected clients, or paste a config snippet for anything else. Restart and you're live.
4. **Ask anything** — use the assistant you already have. It queries your live accounts and answers in plain English.

## Example questions

- "Which keywords have a Quality Score below 5 and spent over $100 this month?"
- "Show me search terms with clicks but zero conversions in the last 30 days."
- "Compare cost per conversion across Google, Meta and TikTok last month."
- "How did organic search traffic change month over month in GA4?"
- "Which TikTok videos have the lowest CPA in the last 14 days?"

## Example custom views

Ask your AI to turn the answer into a view for a client or leadership review — not a locked-in dashboard.

<p align="center">
<img src="https://augurscope.com/showcase/google-ads-dashboard.jpg" alt="Google Ads efficiency view" width="380">
<img src="https://augurscope.com/showcase/growth-review.jpg" alt="Growth review view" width="380">
</p>

## Pricing

**$79, one-time.** Lifetime access, lifetime updates, no subscription. One licence covers 3 computers. 14-day connection guarantee.

[**Get AugurScope →**](https://augurscope.com/#pricing)

## What you'll need

GA4, Meta and TikTok just need you to sign in. Google Ads and Microsoft Ads also require a free developer token you request from your own account — a few minutes of setup, and it's exactly why your data stays yours.

## FAQ

**Does my ad data leave my machine?** No. AugurScope runs locally and queries each platform directly. Your credentials and data never route through us.

**Can it change or break my campaigns?** No. It is strictly read-only — it can query performance data but cannot pause campaigns, edit budgets or change bids.

**Which AI clients does it work with?** Any MCP client, including Claude Desktop, Claude Code, ChatGPT, Cursor, Windsurf and Cline.

**Is there a Mac version?** Windows 10/11 today; macOS is on the roadmap and included free in your purchase.

## Links

[Website](https://augurscope.com) · [Download](https://augurscope.com/download) · [Pricing](https://augurscope.com/#pricing) · [Support](https://augurscope.com/support) · [Privacy](https://augurscope.com/privacy) · [Terms](https://augurscope.com/terms)

## License

AugurScope is a commercial, proprietary product. This repository contains documentation only — no application source code. See [LICENSE](./LICENSE).

---

<sub>MCP server for marketers · Google Ads MCP · GA4 MCP · Meta Ads MCP · Microsoft / Bing Ads MCP · TikTok Ads MCP · connect Google Ads to Claude · connect ad accounts to ChatGPT · AI for PPC · marketing analytics in Claude, ChatGPT & Cursor.</sub>
