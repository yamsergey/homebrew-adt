# Homebrew Tap for Android Development Tools

This is a Homebrew tap for installing Android Development Tools (ADT).

## Installation

```bash
brew tap yamsergey/adt
brew install adt-cli
```

## Available Formulae

- **adt-cli** - Unified CLI for Android project analysis and workspace generation

## Usage

After installation, you can use `adt-cli`:

```bash
# Generate workspace.json for Kotlin LSP
adt-cli workspace /path/to/android/project --output workspace.json

# Analyze project structure
adt-cli resolve /path/to/android/project --workspace --output project-analysis.json

# List build variants
adt-cli resolve /path/to/android/project --variants --output variants.json
```

## Requirements

- Java 21 or higher
