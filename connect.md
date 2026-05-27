---
title: "Connect — Aqua Ridge QBO Bridge"
---

# Connecting Aqua Ridge QBO Bridge to QuickBooks Online

Aqua Ridge QBO Bridge is a private, internal tool operated by Matt Libucha. It is not a SaaS product and has no public sign-up.

The operator initiates the QuickBooks Online OAuth handshake locally from the operator's own machine. There is no public-facing "Connect" button: the connection is established once via Intuit's standard OAuth 2.0 authorization flow, after which the refresh token is stored in a local configuration file and used by the locally running Model Context Protocol (MCP) server.

## How the connection works (operator only)

1. Operator runs the local OAuth flow on their machine
2. Browser redirects to Intuit's authorization page
3. Operator authorizes the app against Matt Libucha's own QuickBooks Online company
4. Intuit issues a refresh token, stored locally on the operator's machine
5. The MCP server uses the refresh token to obtain short-lived access tokens for API calls

For questions: matt@aquaridgeseniorliving.com.
