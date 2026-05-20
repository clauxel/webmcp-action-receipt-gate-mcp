# WebMCP Action Receipt Gate

WebMCP Action Receipt Gate is a hosted remote MCP for WebMCP action receipt MCP.

This repository is a public documentation project for WebMCP Action Receipt Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://webmcpactionreceipt.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=readme_home
- Pricing: https://webmcpactionreceipt.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=readme_pricing
- Checkout: https://webmcpactionreceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://webmcpactionreceipt.clauxel.com/mcp
- Server card: https://webmcpactionreceipt.clauxel.com/server-card.json
- Registry name: `com.clauxel.webmcpactionreceipt/webmcpactionreceipt-mcp`
- Tools: `check_web_action_receipt`, `issue_action_receipt`, `explain_action_policy`, `log_action_attempt`, `export_action_audit`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_web_action_receipt
- MCP tool: issue_action_receipt
- MCP tool: explain_action_policy
- MCP tool: log_action_attempt
- MCP tool: export_action_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
