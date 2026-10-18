[![Proxy: ad library MCP for Meta, Google, LinkedIn and TikTok](assets/banner.png)](https://useproxy.dev/?utm_source=github&utm_medium=readme&utm_campaign=proxy-mcp)

# Proxy: Ad Library MCP Server

[![smithery badge](https://smithery.ai/badge/useproxy/proxy)](https://smithery.ai/servers/useproxy/proxy)

Free MCP server for the public ad libraries of **Meta, Google, LinkedIn and TikTok**. See what any brand is running right now, analyze image and video creatives, find competitors and get a competitive brief, from Claude, ChatGPT, Cursor or any MCP client. No API keys: sign in once with OAuth.

**[Get started free at useproxy.dev →](https://useproxy.dev/welcome?utm_source=github&utm_medium=readme&utm_campaign=proxy-mcp)**

## Connect

Endpoint: `https://mcp.useproxy.dev/mcp` (streamable HTTP, OAuth)

- **Any client:** follow [useproxy.dev/welcome](https://useproxy.dev/welcome?utm_source=github&utm_medium=readme&utm_campaign=proxy-mcp).
- **Command line:** `curl -sL useproxy.dev/install | sh` configures your installed agents.
- **Claude Code:** `claude mcp add --transport http proxy https://mcp.useproxy.dev/mcp`
- **Config file:** copy [`.mcp.json`](.mcp.json) into your client.

## What it does

- **Brand lookup:** find a brand's Meta and Google platform IDs.
- **Ad retrieval:** pull currently running Meta and Google ads, LinkedIn ads by company, keyword or ID, and TikTok ads by advertiser name.
- **Keyword search:** find Meta ads by topic, with no brand needed.
- **Ad details:** full creative variations, targeting and impression data where the platform exposes it.
- **Creative analysis:** describe ad images, and transcribe and analyze video ads.
- **Competitors:** discover competitors from a name, domain or market description, then pull their ads.
- **Competitive brief:** a structured summary of a brand's advertising.
- **Carousel widget:** render ads inline in clients that support MCP apps.

Read-only: it cannot create or publish ads, and private performance data such as conversion rate or ROAS is not available.

## Example prompts

- "How many ads is Anthropic running on Meta, and what's the split between video and image?"
- "Compare the advertising strategies of Nike, Adidas and Under Armour."
- "Who are Canva's main competitors? Show me what they run on Google."
- "Transcribe Anysphere's first TikTok ad."
- "Analyze Nike's top video ads and write three scripts in the same structure for my product."

## Tools

`get_meta_platform_id` · `get_meta_ads` · `search_meta_ads_by_keyword` · `get_google_platform_id` · `get_google_ads` · `get_google_ad_details` · `search_linkedin_ads` · `get_linkedin_ad_details` · `search_tiktok_ads` · `get_tiktok_ad_details` · `search_competitors` · `get_competitive_brief` · `analyze_ad_image` · `analyze_ad_video` · `show_ad_carousel` · `get_credit_balance` · `submit_feedback`

## Related

- [Claude plugin](https://github.com/proxy-intell/claude-plugin) with ready-made competitor research and ad-script skills
- [Cursor plugin](https://github.com/proxy-intell/cursor-plugin)
- [Self-hostable Facebook Ads Library MCP](https://github.com/proxy-intell/facebook-ads-library-mcp) (open source, bring your own keys)

[Website](https://useproxy.dev/?utm_source=github&utm_medium=readme&utm_campaign=proxy-mcp) · [Privacy](https://useproxy.dev/privacy) · [Terms](https://useproxy.dev/terms) · [Support](https://useproxy.dev/support)
