# Username Sniper Tool

A powerful Roblox username checking tool with multiple search modes and GitHub integration for shared taken username databases.

## Features

- 🔍 **Multiple Search Modes**
  - Single Username Check
  - Custom Word-based Username Search
  - Barcode-style Username Search
  - 5 Character Username Search
  - Rescan Available Files

- ☁️ **GitHub Integration**
  - Automatic sync of taken usernames to GitHub
  - Shared database prevents duplicate scans
  - Safe updates prevent data loss

- 🔐 **User Authentication**
  - Account creation and login system
  - Subscription-based access
  - HWID protection

## How It Works

### Taken Usernames (Shared on GitHub)
- All **taken** usernames are automatically uploaded to GitHub
- Everyone shares the same database to avoid duplicate scans
- Automatically fetched before scanning to skip known taken usernames

### Available Usernames (Private)
- **Available** usernames stay on your local computer only
- Not uploaded to GitHub - completely private
- Stored in the `available/` folder on your computer

## Installation

step one dont be stupid

## Usage

1. **Create an account** or **login** with existing credentials
2. **Redeem a key** if you have one (or join Discord for a key)
3. Select a search mode from the menu
4. Follow the prompts to start scanning

## Search Modes

### 1. Single Username Check
Check a single username to see if it's available or taken.

### 2. Custom Word-based Username
Search for usernames based on a custom keyword with word combinations.

### 3. Barcode-style Username
Generate and check barcode-style usernames (14-20 characters using 'I' and 'l').

### 4. 5 Character Search
Generate and check random 5-character usernames.

### 5. Rescan Available Files
Recheck usernames from your available files to verify they're still available.

## GitHub Integration

The tool uses GitHub as a shared database for taken usernames:

- **TakenBarcodes** - Shared barcode-style taken usernames
- **TakenCustom** - Shared custom taken usernames
- **TakenFive_Char** - Shared five character taken usernames
- **TakenSingle_Check** - Shared single check taken usernames

All taken usernames are automatically:
- ✅ Uploaded to GitHub when found
- ✅ Fetched from GitHub before scanning
- ✅ Preserved during updates (no data loss)

## File Structure

```
.
├── 6Lsniper.py              # Main script
├── KeyGenForPaidUsers.py    # Admin key management tool
├── available/               # Local available usernames (private)
│   ├── barcodes.txt
│   ├── custom.txt
│   ├── five_char.txt
│   └── single_check.txt
└── taken/                   
    └── empty needs to be removed
```

## Requirements

a brain

## Notes

- Available usernames are stored locally and are **never** uploaded to GitHub
- Taken usernames are shared on GitHub to help everyone avoid duplicate scans
- The tool automatically handles all GitHub sync operations
- No manual sync needed - everything works automatically

## Support

For support, keys, or questions, join our Discord: https://discord.gg/ZwcSF2F5T7

## License

Private - All rights reserved

