---
name: nitrosend-email
description: Prepare and review Nitrosend email campaigns, flows, audiences and results in the selected account and brand.
---

# Nitrosend email

Use this skill when someone asks to work on email marketing or transactional messaging in their Nitrosend account.

1. Connect through the bundled remote MCP and complete Nitrosend's OAuth flow. Call the current status tool, `nitro_get_status`, to identify the selected account and brand. If the tool is unavailable, inspect the connection and live tool list; do not assume an account or invent tool arguments.
2. Confirm the intended brand, sending domain and audience before preparing a campaign, automation flow, template, segment or transactional message. Use `nitro_search_docs` when a product behavior or setup step is unclear, and follow the current tool schema.
3. Keep drafts and tests distinct from live delivery. Review the visible content, sender, recipients, consent/suppression state and readiness checks with the user before a live send or import. A draft, queued request or successful test is not proof that a campaign reached recipients.
4. For account or brand switches, use the current account-selection tools explicitly and re-read status before acting. Do not carry a sender or audience assumption from a prior brand.
5. After an authorized action, read back its provider ID and current state. Report delivery or performance only from Nitrosend's returned evidence; describe pending or failed states as such.

The [MCP guide](https://docs.nitrosend.com/mcp) documents connection and authentication. This extension holds no API key, sender credential or customer data. The separate [Nitrosend CLI, API and SDK documentation](https://docs.nitrosend.com/) covers non-Gemini integration paths.
