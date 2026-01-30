# Homebrew Tap for Kalo

This is the official Homebrew tap for [Kalo CLI](https://github.com/kalo-build/kalo-cli).

## Installation

```bash
# Install directly (recommended)
brew install kalo-build/tap/kalo

# Or tap first, then install
brew tap kalo-build/tap
brew install kalo
```

## Update

```bash
brew update
brew upgrade kalo
```

## Uninstall

```bash
brew uninstall kalo
brew untap kalo-build/tap  # optional
```

## Available Formulas

| Formula | Description |
|---------|-------------|
| `kalo` | Kalo CLI - Plugin-based code generation and database management |

## About Kalo

Kalo CLI is a modern tool for running atomically composable specification (Morphe, OpenAPI, ...) compilation plugins using WebAssembly (WASM). It enables seamless compilation of schemas across different formats through a flexible plugin system.

Learn more at [github.com/kalo-build/kalo-cli](https://github.com/kalo-build/kalo-cli)
