# Markdown Logic plugins for Claude

Claude plugin packages for [Markdown Logic](https://markdownlogic.com/), version 0.2.0.

| Plugin | Folder | Connection |
| --- | --- | --- |
| Markdown Logic Public | [claude-public](claude-public/) | Anonymous Markdown conversion to PDF, DOCX, HTML or EPUB |
| Markdown Logic | [claude-main](claude-main/) | Team document workflows through browser OAuth |

Each folder contains its own plugin manifest, remote MCP configuration, Skills, documentation, and license notices. See the folder README for setup, capabilities, and limits.

## Directory submission

Submit each folder separately through [Claude's developer portal](https://claude.ai/directory/manage), choosing **Plugin bundle** and this repository. Use `claude-public` or `claude-main` as the plugin path and `main` as the tracked branch.

The hosted MCP servers are separate connector submissions. The public endpoint is `https://markdownlogic.com/mcp`; the authenticated endpoint is `https://mcp.markdownlogic.com`.

These packages are locally validated. Publication of this repository does not establish directory approval, live-client compatibility, or completion of connector qualification.

## License and support

The integration files in this repository are licensed under the [MIT License](LICENSE), with the exclusions in [License scope and notices](LICENSE-SCOPE.md).

Support: support@markdownlogic.com · [Privacy](https://markdownlogic.com/privacy) · [Documentation](https://markdownlogic.com/help/en/connect-an-ai-assistant.html)
