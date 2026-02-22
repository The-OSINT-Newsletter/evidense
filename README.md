# Evidence Case Manager

A case management tool for Obsidian that helps you organize evidence and identifiers for person search investigations.

## Features

- **Create Cases**: Start a new investigation case with a name and description
- **Add Identifiers**: Track multiple identifier types for each case:
  - Names
  - Email addresses
  - Phone numbers
  - Usernames
  - Domains
  - Images
- **Organized Storage**: Each case gets its own folder with metadata and identifier tracking
- **Metadata Tracking**: Automatically records when identifiers were added and any notes

## Installation

1. Copy this folder to your Obsidian plugins folder: `.obsidian/plugins/evidence-case-manager`
2. Reload Obsidian
3. Enable the plugin in Settings > Community Plugins > Evidence Case Manager

## Usage

### Creating a Case

1. Open the command palette (Cmd/Ctrl + P)
2. Search for "Create New Case"
3. Enter a case name (e.g., "Person Search - John Doe")
4. Add a description (optional)
5. Click "Create Case"

### Adding Identifiers

1. Open the command palette (Cmd/Ctrl + P)
2. Search for "Add Identifier to Case"
3. Select the case you want to add to
4. Choose the identifier type (Name, Email, Phone, Username, Domain, or Image)
5. Enter the identifier value
6. Add optional notes about where it came from or how you verified it
7. Click "Add Identifier"

### Case Structure

Each case creates a folder with:
- `case.json` - Metadata and identifier list in JSON format
- `identifiers.md` - Human-readable markdown view of all identifiers organized by type

## Settings

- **Case Folder**: Choose where case folders are stored in your vault (default: "Cases")

## Development

```bash
npm run dev      # Start development mode with watch
npm run build    # Build for production
```

## Support

For issues, feature requests, or questions, please create an issue in the repository.
