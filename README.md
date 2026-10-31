# Synter skill for Amp

Adds the Synter MCP server to Amp as a skill, so Synter tools load only when the skill is used (Amp's recommended setup).

## Install
Copy `skills/synter/` into your project's `.agents/skills/` (or your user skills folder), then ask Amp about your ads. Amp opens a browser sign-in the first time.

Prefer always-on? `amp mcp add synter https://mcp.synterai.com`
Need it in orbs or Amp web too? `amp mcp remote --personal add Synter https://mcp.synterai.com --auth oauth`

Hosted server: 43 ad platforms. Reads are free; $0.25 per verified write, 0% of ad spend.
Local npm package (16 platforms, API key): see https://github.com/Synter-Media-AI/mcp-server

More: https://synterai.com/amp?utm_source=amp-skill
