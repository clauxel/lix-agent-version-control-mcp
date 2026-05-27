# Quickstart

Lix Agent Version Control is a hosted remote MCP for Lix.

## Fast Path

1. Open Lix Agent Version Control and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://lixversion.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call create_agent_change_set with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://lixversion.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=lixversion_public_docs&utm_content=quickstart_home
- https://lixversion.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=lixversion_public_docs&utm_content=quickstart_pricing
- https://lixversion.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=lixversion_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://lixversion.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
