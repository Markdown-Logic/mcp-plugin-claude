# Markdown Logic plugins for Claude

Claude plugin packages for [Markdown Logic](https://markdownlogic.com/), version 0.2.0.

| Plugin | Source | Package ZIP |
| --- | --- | --- |
| Markdown Logic Public | [claude-public](claude-public/) | [claude-public-0.2.0.zip](dist/claude-public-0.2.0.zip) |
| Markdown Logic | [claude-main](claude-main/) | [claude-main-0.2.0.zip](dist/claude-main-0.2.0.zip) |

The public plugin converts complete supplied Markdown to PDF, DOCX, HTML or EPUB without an account. The authenticated plugin supports team document workflows through browser OAuth. Each source folder includes its own manifest, remote MCP configuration, Skills, setup documentation, and license notices.

Package ZIPs match the corresponding source folders. Verify downloads against [SHA256SUMS](dist/SHA256SUMS):

```sh
cd dist
shasum -a 256 -c SHA256SUMS
```

## Connections

| Profile | MCP endpoint | Authentication |
| --- | --- | --- |
| Public | `https://markdownlogic.com/mcp` | None |
| Team documents | `https://mcp.markdownlogic.com` | Browser OAuth |

See each source folder's README for setup, capabilities, and limits.

## Directory submission

Submit each source folder separately through [Claude's developer portal](https://claude.ai/directory/manage), choosing **Plugin bundle** and this repository. Use `claude-public` or `claude-main` as the plugin path and `main` as the tracked branch. Claude reads the source from GitHub; the package ZIPs are provided as matching downloads.

The hosted MCP servers are separate connector submissions. Follow [Claude's plugin submission instructions](https://claude.com/docs/plugins/submit) and [connector submission instructions](https://claude.com/docs/connectors/building/submission), resolve automated findings, and complete the review materials before submitting.

These packages are locally validated. Publication of this repository does not establish directory approval, live-client compatibility, or completion of connector qualification.

## License and support

The integration files in this repository are licensed under the [MIT License](LICENSE), with the exclusions in [License scope and notices](LICENSE-SCOPE.md).

Support: support@markdownlogic.com · [Privacy](https://markdownlogic.com/privacy) · [Documentation](https://markdownlogic.com/help/en/connect-an-ai-assistant.html)
