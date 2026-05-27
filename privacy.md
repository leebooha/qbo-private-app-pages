---
title: "Privacy Policy — Aqua Ridge QBO Bridge"
---

# Privacy Policy

_Last updated: 2026-05-27_

This Privacy Policy describes how Aqua Ridge QBO Bridge ("the Software") handles data. The Software is a private, internal tool operated by Matt Libucha for the sole purpose of accessing Matt Libucha's own QuickBooks Online company.

## Who this policy applies to

The Software has no public-facing end users. It is operated only by Matt Libucha and authorized personnel within Matt Libucha's organization. This policy describes the handling of data accessed by the Software on behalf of Matt Libucha itself.

## Data accessed

The Software accesses data from Matt Libucha's own QuickBooks Online company via the Intuit QuickBooks Online API, including:

- Accounting records (invoices, bills, payments, journal entries, deposits, transfers, etc.)
- Lists (customers, vendors, employees, items, accounts, classes, departments)
- Reports (balance sheet, profit & loss, cash flow, aged receivables, aged payables, trial balance, general ledger)
- Company profile information
- Tax codes, rates, and agencies
- File attachments associated with transactions

The Software does **not** access data from any QuickBooks Online company other than Matt Libucha's own.

## How data is used

Data is used solely to support Matt Libucha's internal bookkeeping and financial workflows. It is processed in response to operator-initiated requests and is not used for advertising, profiling, model training, resale, or any purpose unrelated to Matt Libucha's own accounting.

## Where data is stored

- Data fetched from the QuickBooks Online API is held in memory on the operator's local machine while the Software is running
- OAuth tokens (refresh token and access token) are stored locally in a configuration file on the operator's machine, used solely to authenticate to the QuickBooks Online API
- The Software does not maintain a persistent database of QuickBooks data; data is fetched on-demand per request
- The Software does not transmit QuickBooks data to any third party

## Sharing

QuickBooks data accessed by the Software is **not** shared with any third party. It does not leave the operator's local environment except as needed to call the Intuit QuickBooks Online API itself.

## Retention

The Software does not retain QuickBooks data beyond the duration of an active session. OAuth tokens are retained until they are revoked or replaced through Intuit's standard token rotation.

## Security

OAuth tokens are stored in a local configuration file on the operator's machine. The operator is responsible for the security of that machine and configuration file, in accordance with standard credential-handling practice.

## End-user rights

Because the Software has no end users other than Matt Libucha itself, there is no end-user data subject whose access, deletion, or portability rights would apply against the Software. Rights regarding the QuickBooks data itself are governed by Intuit's own privacy policy and Matt Libucha's relationship with Intuit.

## Changes to this policy

This policy may be updated as the Software evolves. The "Last updated" date above reflects the most recent revision.

## Contact

Privacy-related questions: matt@aquaridgeseniorliving.com.
