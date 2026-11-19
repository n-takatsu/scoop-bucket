# n-takatsu Scoop bucket

[Scoop](https://scoop.sh/) bucket for [mcp-rs](https://github.com/n-takatsu/mcp-rs), an MCP server that gives AI clients tools for WordPress, databases (PostgreSQL, MySQL, MariaDB) and external MCP plugins.

```powershell
scoop bucket add n-takatsu https://github.com/n-takatsu/scoop-bucket
scoop install n-takatsu/mcp-rs
mcp-rs init
```

Update with `scoop update mcp-rs`, then restart the MCP clients. See the [Getting Started guide](https://n-takatsu.github.io/mcp-rs/docs/guides/#package-managers).

The manifest installs the ready-built mcp-rs (Windows x64) from the [mcp-rs releases](https://github.com/n-takatsu/mcp-rs/releases) and checks its SHA256. A daily workflow updates it to the latest release, after installing it to test. The source of the manifest is [`packaging/scoop/mcp-rs.json`](https://github.com/n-takatsu/mcp-rs/blob/develop/packaging/scoop/mcp-rs.json) in the mcp-rs repository. Report problems in [mcp-rs issues](https://github.com/n-takatsu/mcp-rs/issues).
