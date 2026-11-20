# Alauda HELOC Rates

Use this agent skill to look up public HELOC rate ranges in California and Florida through Alauda’s hosted MCP service. The skill tells the assistant how to request and interpret advertised rates, including their observation dates and geographic coverage.

## Try it

1. Connect an MCP-capable client to `https://mcp.alauda.ai/mcp` using Streamable HTTP. See the [official connection guide](https://www.alauda.ai/for-ai-agents?utm_source=github&utm_medium=referral&utm_campaign=heloc_skill).
2. Run `npx skills add detongz/alauda-home-equity --skill alauda-heloc-rates` and choose your agent.
3. Ask “What HELOC rates does Alauda’s public Florida sample show, and when were they observed?”

The public comparison uses a state and a product. Advertised rates can change. Check the lender’s own disclosure for the terms of a particular offer.

## Registry listing

[View the published remote server](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.detongz%2Falauda-home-equity/versions/latest). This repository contains the community-maintained connection instructions and skill. The remote service runs at mcp.alauda.ai.
