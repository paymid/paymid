# Paymid

**The middleman gets paid first.**

Paymid is commission protection for middlemen everywhere. When a broker, agent or connector puts a deal together, Paymid sequences the deal so the commission is confirmed before the contact is released and the main payment moves, and keeps a verifiable record of the whole bridge.

Paymid never holds the deal money. The parties pay each other on their own rails: Pix, ACH, wire, SEPA, Zelle, PayPal, card, Bitcoin. Paymid is the order and the proof.

## Connect Paymid to your AI assistant

Paymid is an MCP server. In ChatGPT, Claude and other MCP clients, add the remote server:

- Server URL: https://mcp.paymid.com.br/mcp/claude
- Sign-in: OAuth 2.1, account created inline in seconds, email and password only.

Or install the stdio package:

- PyPI: paymid-mcp (uvx paymid-mcp)
- CrewAI: crewai-paymid

## What it does

- Creates a bridge with the deal, the commission and the parties.
- Fee inside the commission: 1.5% of the commission + 0.1% of the deal value, capped.
- Releases a sealed contact only after the commission is confirmed.
- Issues a tamper-evident record of the agreement and every step.

## This repository

Manifests and integration files only. server.json is the MCP Registry manifest. The Paymid application itself is not open source.

- Website: https://paymid.com.br
- Docs: https://paymid.com.br/docs
- Terms: https://paymid.com.br/terms
- Privacy: https://paymid.com.br/privacy
- Support: contact@aufwassen.com
