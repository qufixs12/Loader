# Username Sniper by 6LSniper

**Made by: richfucks** | [Discord Server](https://discord.gg/ZwcSF2F5T7)

A powerful username availability checker tool that allows you to find available usernames. Features account management, license key system, and multiple search modes.

## 📋 Features

### 🔐 Account System
- **Secure Account Creation** - Create your account with username, password, and email
- **Account Login** - Secure login with HWID tracking
- **Account Status** - View your subscription status, expiry countdown, and account details
- **Recovery Keys** - Unique recovery keys for HWID switches (3 switches allowed)

### 🔑 License Key System
- **Key Redemption** - Redeem license keys (1-week, 1-month, lifetime)
- **Subscription Tracking** - Automatic subscription expiry tracking with countdown
- **Key Sharing Prevention** - Strict zero-tolerance policy against key sharing

### 🔍 Search Modes

1. **Single Username Check** - Check if a specific username is available
2. **Custom Word-based Username** - Search for usernames based on custom keywords
3. **Barcode-style Username** - Generate and check barcode-style usernames (14-20 characters)
4. **5 Character Search** - Search for any 5-character usernames (letters, numbers, underscores)
5. **Rescan Available Files** - Rescan previously found available usernames

### 💾 File Management
- **Organized Storage** - Results saved in `available/` and `taken/` folders
- **Multiple Output Files** - Separate files for each search mode
- **Rescan Capability** - Recheck previously found usernames

## 🚀 Getting Started

### Installation
1. Download the `6LSniper.exe` file
2. Place it in a folder of your choice
3. Run the executable

### First Time Setup

1. **Create an Account**
   - Run the executable
   - Select option `2` to create a new account
   - Enter your username (minimum 4 characters)
   - Enter your password (minimum 3 characters)
   - Enter your email address
   - Consent to data storage by typing `yes`

2. **Redeem a License Key**
   - After account creation, you'll be prompted to redeem a key
   - Enter your license key (format: `LIFETIME-KEY-ABC123`)
   - Your subscription will be activated automatically

## 📖 Usage Guide

### Main Menu Options

```
1. Single Username Check
   - Enter a specific username to check its availability

2. Custom Word-based Username
   - Enter a keyword and position (start/end)
   - Generates combinations with numbers/underscores

3. Barcode-style Username
   - Choose length (14-20 characters)
   - Generates random barcode-style usernames

4. 5 Character Search
   - Automatically generates and checks 5-character usernames

5. Rescan Available Files
   - Recheck usernames from previous searches
   - Choose which file to rescan

6. Account Status
   - View subscription countdown
   - View account details and recovery key

Q. Quit
```

### During Search

- **Press `x`** - Stop the current search and return to main menu
- **Press `1`** - Go back to main menu when prompted

### Search Results

- **Available Usernames** - Saved to `available/[mode].txt`
- **Taken Usernames** - Saved to `taken/[mode].txt`
- Results are automatically organized by search mode

## ⚠️ Important Notes

### Key Sharing Policy

**ZERO TOLERANCE POLICY - KEY SHARING IS STRICTLY PROHIBITED**

- **Warning System**: Users receive warnings (1/3, 2/3) for key sharing attempts
- **Account Deletion**: After 3 attempts, both accounts (key sharer and redeemer) are **PERMANENTLY DELETED**
- **Key Revocation**: The license key is permanently revoked and deleted
- **No Refunds**: This action is irreversible. No refunds. No appeals.

### HWID System

- Each account is tied to your Hardware ID (HWID)
- **3 HWID switches allowed** per account
- Use your recovery key to switch HWID
- If you exceed 3 switches, contact support on Discord

### Account Security

- **Banned Accounts**: Banned users cannot log in
- **Recovery Keys**: Keep your recovery key safe - it's unique to your account
- **Password**: Cannot be recovered if lost


## 📁 File Structure

```
6Lsniper/
├── 6LSniper.exe    # Main executable
├── available/                       # Available usernames
│   ├── custom.txt
│   ├── barcodes.txt
│   ├── five_char.txt
│   └── single_check.txt
└── taken/                          # Taken usernames
    ├── custom.txt
    ├── barcodes.txt
    ├── five_char.txt
    └── single_check.txt
```

## 🔧 System Requirements

- **OS**: Windows 10/11
- **Internet Connection**: Required for access and username checking
- **No Installation Required**: Just run the executable

## 📞 Support

- **Discord Server**: (https://discord.gg/ZwcSF2F5T7)

## ⚖️ License & Terms

- This software is provided as-is
- Account creation requires consent to data storage
- License keys are non-transferable
- Zero tolerance for key sharing
- All actions are logged and tracked

## 🔒 Privacy & Security

- User data is stored securely
- HWID tracking for security
- IP addresses are logged
- Recovery keys are unique and encrypted
- All communication is encrypted

## 📝 Changelog

### Current Version Features
- ✅ Account creation and login system
- ✅ License key redemption system
- ✅ Multiple search modes
- ✅ File organization (available/taken folders)
- ✅ HWID tracking and recovery keys
- ✅ Key sharing prevention with warnings
- ✅ Subscription countdown display
- ✅ Clean, user-friendly interface
- ✅ Stop search functionality (press 'x')

---

**⚠️ REMINDER**: Do not share your license keys. Key sharing will result in permanent account deletion with no refunds or appeals.

**Made ❤️ by richfucks**

