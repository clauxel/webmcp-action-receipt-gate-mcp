# Quickstart

WebMCP Action Receipt Gate is a hosted remote MCP for WebMCP action receipt MCP.

## Fast Path

1. Open WebMCP Action Receipt Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://webmcpactionreceipt.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_web_action_receipt with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://webmcpactionreceipt.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=quickstart_home
- https://webmcpactionreceipt.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=quickstart_pricing
- https://webmcpactionreceipt.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=webmcpactionreceipt_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://webmcpactionreceipt.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
