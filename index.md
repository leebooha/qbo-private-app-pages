---
title: "{{APP_NAME}}"
---

# {{APP_NAME}}

{{APP_NAME}} is a private, internal tool that connects to QuickBooks Online to support {{OPERATOR}}'s own bookkeeping workflows. It is **not** a multi-user product, is not offered as a service to others, and is not available for public sign-up.

## What it does

{{APP_NAME}} accesses QuickBooks Online accounting data — invoices, bills, customers, vendors, journal entries, reports, and related accounting records — via the Intuit QuickBooks Online API. It is operated by {{OPERATOR}} solely against {{OPERATOR}}'s own QuickBooks Online company.

The tool runs locally on the operator's machine as a Model Context Protocol (MCP) server. It does not host data, does not expose a network service to other users, and does not have user accounts.

## Who can use it

Only {{OPERATOR}} and authorized personnel within {{OPERATOR}}'s organization. There is no public sign-up, no end-user UI, and no shared instance.

## Authentication

Authentication is done one time via Intuit's OAuth 2.0 flow. Tokens are stored locally on the operator's machine and used solely to call the QuickBooks Online API on the operator's behalf.

## Policies

- [Terms of Use](./terms.html)
- [Privacy Policy](./privacy.html)

## Contact

For questions, contact {{CONTACT_EMAIL}}.
