# Security policy

How to report a vulnerability in the Plotwork MCP server package, and what to expect. It is for anyone who finds a security problem in the package published from this repository.

## TL;DR

| Question | Answer |
|---|---|
| Where do I report? | Use "Report a vulnerability" on the Security tab of this repository. That report is private. |
| Is there an email address? | No. The private report above is the only channel, so every report stays private until a fix is out. |
| Which versions get fixes? | The latest published version. |
| Should I open a public issue? | No. Public issues are for bugs that are not security problems. |

## What the package does

The package runs read-only diagram tools over standard input and output. It needs no API key. By default it makes no network requests, reads no files, and writes none. Only if you set `PLOTWORK_USAGE` does it count your tool calls in one local file, and only if you set it to `share` does it send pseudonymous daily totals to Plotwork, as the package README describes. A report is most useful when it shows one of the following:

- the package reaching the network, the file system, or another process
- a tool argument that makes the package misbehave or exhaust memory
- a secret or a path of a build machine inside the published files
- a mismatch between a published version and its `checksums.txt`

## What to include

Give the package version (the output of running the package with `--version`), your Node version, the smallest input that shows the problem, and what you expected instead.

## What happens next

The maintainers acknowledge a report, confirm the problem, and publish a fixed version. A published version is never changed or removed. A fix is a new version, and an affected version is deprecated on npm with a pointer to the fix.

## See also

| Link | Why |
|---|---|
| [README](./README.md) | What the package is and how to install it |
| [Documentation](https://docs.plotwork.dev) | The tools and the hosted server |
