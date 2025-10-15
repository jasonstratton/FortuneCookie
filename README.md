# FortuneCookie MCP Server Workshop

A hands-on workshop for building a Model Context Protocol (MCP) server that serves random fortune cookie messages.

## What is Fortune?

The Unix `fortune` command is a classic utility that displays random quotations, jokes, or sayings - essentially digital "fortune cookies." Fortune files contain collections of quotes separated by `%` lines.

## What is MCP?

The Model Context Protocol (MCP) is a standard for connecting AI assistants with external data sources and tools. An MCP server exposes tools and resources that AI models can use to enhance their capabilities.

## Workshop Objective

Build an MCP server that provides fortune cookie functionality to AI assistants. Your server should be able to serve random fortunes from the provided data file.

## Getting Started

1. **Explore the data**: Check out `data/fortunes.txt` to understand the fortune file format
2. **Choose your language**: Implement in Python, TypeScript, Go, Rust, or any language you prefer
3. **Use AI assistance**: Leverage GitHub Copilot, Cursor, or similar tools to help with implementation
4. **Design your MCP server**: Think about what tools/resources your server should expose

## Deliverable

A working MCP server that can:
- Read fortune data from the provided file
- Serve random fortunes via MCP protocol
- Be discoverable and usable by MCP clients

## Resources

- [Wikipedia UNIX “fortune” command](https://en.wikipedia.org/wiki/Fortune_(Unix))
- [MCP specification](https://modelcontextprotocol.io/)
- Use your AI coding assistant to learn MCP server patterns and implementation details
- Fortune data
  - The cookie file format is multiline strings seperated by a '%' char
  - Past implementations have used a directory with multiple data files with methods for filtering the content
  - `data/fortunes.txt` - 3 sample fortunes provided in this repo
  - [classical](https://github.com/HubTou/fortunes-freebsd-classic) and [historical](https://github.com/HubTou/fortunes-historical) cookie files
- fortune implementations
  - [Debian](https://salsa.debian.org/debian/fortune-mod)
  - [C](https://github.com/shlomif/fortune-mod)
  - [Python](https://github.com/bmc/fortune)
  - [Go](https://github.com/bmc/fortune-go/)
 
## Tips

- Start simple - get basic fortune serving working first
- Consider what MCP tools would be most useful (random fortune, fortune by keyword, etc.)
- Test your server with an MCP client to ensure it works
- Document your approach and any interesting design decisions

Happy coding! 🥠
