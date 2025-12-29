# Claude Plugins Marketplace

Custom plugins for Claude Code by SERGIUSH-UA.

## Installation

```bash
# Add marketplace
claude plugin marketplace add SERGIUSH-UA/claude-plugins-marketplace

# Install plugin
claude plugin install bsl-lsp@sergiush-ua-plugins
```

## Update

```bash
# Update marketplace
claude plugin marketplace update sergiush-ua-plugins

# Update plugin
claude plugin update bsl-lsp
```

## Available Plugins

### bsl-lsp

LSP support for 1C:Enterprise 8 (BSL) and OneScript.

**Features:**
- Go to Definition
- Find References
- Document Symbols
- Hover information
- Diagnostics (errors/warnings)
- Call Hierarchy

**Supported files:**
| Extension | Description |
|-----------|-------------|
| `.bsl` | 1C:Enterprise 8 modules |
| `.os` | OneScript files |

**Requirements:**
- Java 21+ (LibericaJDK recommended)
- BSL Language Server JAR

**Post-install setup:**

Download BSL Language Server JAR from [releases](https://github.com/1c-syntax/bsl-language-server/releases) and place it in the plugin's `bin/` directory.

## Resources

- [BSL Language Server](https://github.com/1c-syntax/bsl-language-server)
- [Claude Code Plugins](https://docs.anthropic.com/claude-code/plugins)
