# Karamble's CasaOS AppStore

A custom CasaOS AppStore featuring Decred ecosystem applications.

## 🚀 Apps Included

### dcrpulse
**Decred blockchain explorer and wallet dashboard with full node**

dcrpulse is a comprehensive Decred blockchain explorer and wallet dashboard combining a full dcrd node, dcrwallet, and an intuitive web interface. Monitor the Decred network, manage your wallet, and explore transactions all in one secure, self-hosted application.

**Features:**
- Full Decred node (dcrd v2.1.0) with blockchain synchronization
- Integrated wallet (dcrwallet v2.1.0) with HD wallet support
- Real-time mempool monitoring and transaction tracking
- Block explorer with transaction categorization
- Wallet management with xpub import and address generation
- Network-isolated backend services for enhanced security
- No external dependencies or third-party APIs

**Category:** Finance

[View dcrpulse on GitHub](https://github.com/karamble/dcrpulse)

---

## 📦 How to Add This Store to CasaOS

### Prerequisites
- CasaOS v0.4.4 or newer

### Installation Steps

1. **Open CasaOS Settings**
   - Click on your profile icon in the top right corner
   - Select "Settings" from the dropdown menu

2. **Navigate to App Store Settings**
   - In the Settings sidebar, click on "App Store"
   - Scroll down to the "Third-Party App Stores" section

3. **Add Custom App Store**
   - Click the "+ Add Source" button
   - Enter the following archive URL:
     ```
     https://github.com/karamble/karambles-casaos/archive/refs/heads/master.zip
     ```
   - Click "Add" to save
   - CasaOS will download and process the app store

4. **Refresh App Store**
   - Return to the CasaOS App Store main page
   - Click the refresh icon or reload the page
   - You should now see "Karamble's AppStore" in your app store sources

5. **Install dcrpulse**
   - Browse to the Finance category or search for "dcrpulse"
   - Click on the dcrpulse card
   - Click "Install" and follow the installation wizard
   - **Note:** Initial blockchain sync takes 4-8 hours

### Alternative Installation Methods

**Option 1: GitHub Archive (Recommended)**
```
https://github.com/karamble/karambles-casaos/archive/refs/heads/master.zip
```

**Option 2: jsDelivr CDN**
```
https://cdn.jsdelivr.net/gh/karamble/karambles-casaos@master
```

**Option 3: Direct GitHub Repository**
```
https://github.com/karamble/karambles-casaos
```

Note: CasaOS typically expects a `.zip` archive URL for third-party app stores.

---

## 🔧 System Requirements

### For dcrpulse:
- **Disk Space:** ~15GB for blockchain data
- **RAM:** 4GB minimum recommended
- **Network:** Stable internet connection for initial sync
- **CPU:** Multi-core recommended for optimal performance

---

## 🔐 Security & Privacy

All apps in this store follow best practices for security and privacy:

- **Network Isolation:** Backend services (like dcrwallet) are network-isolated with no internet access
- **No Telemetry:** Apps don't send any usage data or analytics
- **Self-Hosted:** All data stays on your device
- **Open Source:** All applications are open source and auditable

### dcrpulse Network Architecture:
- **dcrd:** Has internet access for blockchain P2P synchronization
- **dcrwallet:** Network-isolated, no internet access (secure)
- **dashboard:** Network-isolated, no internet access (secure)
- Services communicate internally via secure RPC connections

---

## 🤝 Contributing

Have suggestions for additional Decred-related apps to include in this store?

1. Open an issue at: https://github.com/karamble/karambles-casaos/issues
2. Include the app name, description, and GitHub repository link
3. Ensure the app follows CasaOS AppStore guidelines

---

## 📚 Resources

- **CasaOS Official:** https://casaos.io
- **CasaOS Official AppStore:** https://github.com/IceWhaleTech/CasaOS-AppStore
- **CasaOS Contributing Guide:** https://github.com/IceWhaleTech/CasaOS-AppStore/blob/main/CONTRIBUTING.md
- **Awesome CasaOS Stores:** https://awesome.casaos.io/content/3rd-party-app-stores/list.html
- **Decred Project:** https://decred.org
- **dcrpulse Repository:** https://github.com/karamble/dcrpulse

---

## 📋 Store Structure

```
karambles-casaos/
├─ category-list.json       # Category definitions (Finance)
├─ recommend-list.json      # Recommended apps list
├─ featured-apps.json       # Featured apps list
├─ Apps/                    # Application definitions
│  └─ dcrpulse/
│     ├─ docker-compose.yml # CasaOS Docker Compose configuration
│     ├─ icon.png           # App icon (192x192 transparent PNG)
│     ├─ screenshot_1.jpg   # Screenshot 1 (1280x720)
│     ├─ screenshot_2.jpg   # Screenshot 2 (1280x720)
│     └─ screenshot_3.jpg   # Screenshot 3 (1280x720)
└─ README.md                # This file
```

---

## 📄 License

ISC License

Copyright (c) 2015-2024 The Decred developers

Permission to use, copy, modify, and distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

See [LICENSE](LICENSE) file for full details. Individual apps may have their own licenses - see their respective repositories.

---

## 🌟 Support

If you find this app store useful, consider:
- ⭐ Starring this repository
- 🐛 Reporting issues or bugs
- 💡 Suggesting new Decred-related apps
- 🤝 Contributing to the Decred ecosystem

---

**Maintained by:** [@karamble](https://github.com/karamble)

**Last Updated:** November 2025

