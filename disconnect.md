---
title: "Disconnect — Aqua Ridge QBO Bridge"
---

# Disconnecting Aqua Ridge QBO Bridge from QuickBooks Online

Aqua Ridge QBO Bridge is a private, internal tool with no end users other than the operator (Matt Libucha). Disconnection is handled by the operator, either by:

1. Revoking the app's authorization from within QuickBooks Online (Settings → Apps → Connected Apps), or
2. Removing the stored OAuth refresh token from the operator's local configuration file

When either of these occurs, the locally running Model Context Protocol (MCP) server can no longer obtain access tokens and stops being able to call the QuickBooks Online API.

## Data handling on disconnect

No QuickBooks data is retained by the Software. All QBO data is held in memory only during active sessions and is not stored persistently. On disconnect, the only artifact removed is the OAuth refresh token in the local configuration file.

For questions: matt@aquaridgeseniorliving.com.
