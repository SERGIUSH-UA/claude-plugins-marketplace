# Claude Plugins Marketplace

Private marketplace for Claude Code plugins.

## Installation

```bash
claude marketplace add git@github.com:YOUR_USERNAME/claude-plugins-marketplace.git
```

## Available Plugins

### bsl-lsp

LSP support for 1C:Enterprise 8 (BSL) and OneScript.

**Requirements:**
- Java 21+ (LibericaJDK recommended)
- BSL Language Server JAR (download separately)

**Setup:**
1. Install the plugin: `claude plugin install bsl-lsp`
2. Download BSL LS JAR from [releases](https://github.com/1c-syntax/bsl-language-server/releases)
3. Place `bsl-language-server.jar` in the plugin's `bin/` directory

**Supported files:**
- `.bsl` - 1C:Enterprise 8 modules
- `.os` - OneScript files
