# Plotwork MCP server

The Plotwork diagram tools as a local MCP (Model Context Protocol) server. An AI agent uses it to read the diagram language, validate source, check an outline, and render twenty kinds of diagram, from flow, sequence, and database to Gantt, state, mind map, and treemap as SVG. It runs on your machine over standard input and output.

## TL;DR

| Question | Answer |
|---|---|
| Does it need an API key? | No. There is no key, no sign-in, and no account. |
| Does it use the network? | Not by default. Every tool is a pure computation over its arguments, and with nothing set it reads no files, writes none, and makes no network request. Only if you set `PLOTWORK_USAGE` does it count your tool calls, and only if you set it to `share` does it send anything. See [Usage counts](#usage-counts-off-unless-you-turn-them-on). |
| How do I start it? | `npx -y @buun_group/plotwork-mcp`. Your MCP client runs this command for you. |
| Which Node version? | Node 22 or newer. |
| What are the tools? | Workflows that draw a diagram, convert Mermaid, choose icons, and sync a Markdown document in one call, and single steps for fine control. All are read-only. Your client lists them, and the tool reference in the documentation has every name and schema. |
| Is there a hosted version? | Yes, at `https://mcp.plotwork.dev`. It needs an API key or a browser sign-in. See [the hosted server](#the-hosted-server). |
| Which licence? | MIT. Code and data from other people keep their own licences, listed in `THIRD-PARTY-NOTICES.md`. See [License](#license). |

## Install

Nothing is installed globally. Your client starts the server with `npx`, and `npx` downloads this package on first use.

### Claude Code

```sh
claude mcp add plotwork -- npx -y @buun_group/plotwork-mcp
```

Then run `/mcp` in Claude Code and check that `plotwork` is connected and lists the Plotwork tools.

### Cursor

Add this to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "plotwork": {
      "command": "npx",
      "args": ["-y", "@buun_group/plotwork-mcp"]
    }
  }
}
```

### VS Code

Add this to `.vscode/mcp.json`:

```json
{
  "servers": {
    "plotwork": {
      "type": "stdio",
      "command": "npx",
      "args": ["-y", "@buun_group/plotwork-mcp"]
    }
  }
}
```

### Claude Desktop

Add this to `claude_desktop_config.json`, then restart Claude Desktop:

```json
{
  "mcpServers": {
    "plotwork": {
      "command": "npx",
      "args": ["-y", "@buun_group/plotwork-mcp"]
    }
  }
}
```

### Other clients

Any client that starts an MCP server as a local process takes the same two parts: the command `npx` and the arguments `-y @buun_group/plotwork-mcp`.

## Check it by hand

```sh
npx -y @buun_group/plotwork-mcp --version
npx -y @buun_group/plotwork-mcp --help
```

Run with no arguments, `plotwork-mcp` waits for an MCP client on standard input. Standard output carries only protocol messages. One log line per tool call goes to standard error, with the tool, the outcome, the duration, and the size of the arguments. The contents of the arguments are never logged.

## Usage counts (off unless you turn them on)

By default the package counts nothing and keeps no file. You can ask it to count how often each tool is used on your own machine, and, separately, to send pseudonymous daily totals to Plotwork so the project can see which tools matter. Both are off until you set `PLOTWORK_USAGE` in the `env` block of your client or in your shell. There is no config file, so nothing is switched on out of sight.

| Setting | What it does |
|---|---|
| `PLOTWORK_USAGE` unset, empty, or any other value | Off. Nothing is counted, saved, or sent. |
| `PLOTWORK_USAGE=local` | Counts calls on this device, in one file, `usage.json`. Nothing is sent. |
| `PLOTWORK_USAGE=share` | Counts the same way, and once a day sends the totals of each finished day. |
| `DO_NOT_TRACK=1` (or `true`) | Caps the setting at `local`, so nothing is ever sent, whatever else is set. |
| `PLOTWORK_HOME` | The folder for `usage.json`. The default is `.plotwork` in your home folder. |

Only counts are kept. A count is a tool name, the diagram kind the source declared (`flow`, `sequence`, `schema`, or `none`), how the call ended (`ok`, `rejected`, or `error`), and a number, for each UTC day. Diagram source, arguments, names, file paths, error messages, your host name and user name, and the time of day are never counted or sent.

What `share` sends is a small JSON body with those counts, a pseudonym for the month (a keyed hash that changes every month, so Plotwork can count active installs in a month but cannot follow one from month to month), the package version, your operating system family, and the Node major version. It carries no cookie, no account, and no key. It never sends today, never follows a redirect, gives up after three seconds, and fails silently.

You can look at all of it before you decide:

```sh
npx -y @buun_group/plotwork-mcp usage            # the setting, the counts of the last 30 days, and the next send
npx -y @buun_group/plotwork-mcp usage preview    # the exact request a send would post, or "nothing to send"
npx -y @buun_group/plotwork-mcp usage reset      # delete the file, with its secret and every count
```

These commands never touch the network.

## The hosted server

The hosted server runs the same tools at `https://mcp.plotwork.dev`. Use it when a client cannot start a local process, or when you want one shared endpoint. It is not part of this package, and it asks for a credential.

| Way in | Address | Credential |
|---|---|---|
| API key | `https://mcp.plotwork.dev/mcp` | Create a key at [app.plotwork.dev](https://app.plotwork.dev) and send it in the `X-API-Key` header. |
| Browser sign-in (OAuth) | `https://mcp.plotwork.dev/mcp-oauth` | None to copy. Your client opens a browser and you sign in. |

The documentation has the exact settings for each client.

## License

@buun_group/plotwork-mcp is licensed under the MIT licence. The text is in the file `LICENSE`.

The single file `plotwork-mcp.mjs` also contains code and data that other people wrote: the MCP SDK, the zod validation library, the ELK layout engine, icon artwork, and font measurements. Each keeps its own licence. `THIRD-PARTY-NOTICES.md` lists every one with its version, copyright, and the full licence text. The MIT licence of this package does not replace those licences.

The package includes the official architecture icons of AWS, Microsoft Azure, Google Cloud, unmodified. They belong to their owners and are **not** covered by the MIT licence. Their terms and the trademark notice are in `THIRD-PARTY-NOTICES.md`.

## About this repository

This repository holds the built package that is published to npm, updated by an automated release. A change here is replaced by the next release, so open an issue instead of a pull request. Releases are immutable: a published version is never changed, and a fix is a new version.

Each release carries `checksums.txt` with the SHA-256 of every file in the package, including `LICENSE` and `THIRD-PARTY-NOTICES.md`. To check a download:

```sh
sha256sum --check checksums.txt
```

## See also

| Link | Why |
|---|---|
| [Documentation](https://docs.plotwork.dev) | The diagram language, the tool reference, and client settings |
| [Issues](https://github.com/plotwork-official/plotwork-mcp/issues) | Report a problem or ask a question |
| [Security policy](https://github.com/plotwork-official/plotwork-mcp/security/policy) | Report a vulnerability privately |
