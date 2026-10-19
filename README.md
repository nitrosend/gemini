# Nitrosend for Gemini CLI

<img src="assets/logo.png" alt="Nitrosend mark" width="96" />

Work with your Nitrosend email account from Gemini CLI. The extension connects to Nitrosend's hosted OAuth MCP at `https://api.nitrosend.com/mcp` and includes a guided skill for campaigns, flows, audiences, tests and result readback. It carries the current Nitrosend mark and no credentials or local server.

## Install

```bash
gemini extensions install https://github.com/nitrosend/gemini
```

Gemini CLI loads `gemini-extension.json`, discovers the `nitrosend-email` skill and prompts you to authorize the remote connection when needed. Confirm the selected account and brand before drafting or sending. Live sends and imports should follow the account's consent, sender and readiness checks; a draft or test is not a delivered campaign.

The hosted connector is for Nitrosend account work. The separate [CLI, API and SDK](https://docs.nitrosend.com/) serve terminal and application integrations; this extension does not install them.

[MCP setup](https://docs.nitrosend.com/mcp) · [Privacy](https://nitrosend.com/privacy) · [Terms](https://nitrosend.com/terms) · Contact: `contact@nitrosend.com`

The extension files are [MIT licensed](LICENSE). The Nitrosend service and brand are governed by their own terms.
