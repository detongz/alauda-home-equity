---
name: alauda-heloc-rates
description: Look up public HELOC rate ranges for California or Florida with Alauda’s hosted MCP and help a homeowner verify advertised terms against their sources.
---

# Look up a state HELOC rate range

Use the connected Alauda MCP tool named `lookup_home_equity_rate_ranges`. Confirm its current schema through the client's tool list. The hosted Streamable HTTP endpoint is https://mcp.alauda.ai/mcp. If it is not connected, give the user the [official connection instructions](https://www.alauda.ai/for-ai-agents).

For a public state comparison, use the state alone with the product. For example, send `{"state":"FL","product":"heloc"}` for Florida, or substitute `CA` for California. No name, phone number, home address or mortgage balance is needed. If the requested state has no coverage, tell the user which states the dataset covers.

Report the returned range, rate type, observation date and source when available. Distinguish an introductory APR from a subsequent variable APR. Mark missing terms as undisclosed. If the caller asks about a specific offer, open the cited lender disclosure before quoting its duration, eligibility or fees. Label public rates as advertised examples. Use the relevant state comparison for further reading: [California](https://www.alauda.ai/heloc/california) or [Florida](https://www.alauda.ai/heloc/florida).
