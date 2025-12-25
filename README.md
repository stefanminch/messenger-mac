# Messenger for Mac

A standalone desktop app for Facebook Messenger on macOS. Chat with friends without opening a browser.

![Messenger App Icon](icon.icns)

## Download

**[Download Messenger for Mac (DMG)](https://drive.google.com/file/d/1gWA3tdD3BMk3RQ8kiVbrNgN3NAK-2qAj/view?usp=sharing)** - v1.0.0 | macOS 10.13+

> Signed and notarized by Apple for your security.

## Features

- **Native macOS App** - Runs as a standalone application in your dock
- **No Browser Required** - Access Messenger without opening Chrome, Safari, or Firefox
- **Persistent Login** - Stay logged in between app restarts
- **Native Notifications** - Get notified of new messages
- **Minimal & Fast** - Lightweight app with low memory footprint
- **Privacy Focused** - No tracking, no analytics, no data collection
- **Dark Mode Support** - Follows your macOS appearance settings
- **Keyboard Shortcuts** - Standard macOS shortcuts work as expected

## Screenshots

| Chat View | Login |
|-----------|-------|
| Native macOS window | Secure Facebook login |

## Installation

1. Download the [DMG file](https://drive.google.com/file/d/1gWA3tdD3BMk3RQ8kiVbrNgN3NAK-2qAj/view?usp=sharing)
2. Open the DMG
3. Drag **MessengerApp** to your **Applications** folder
4. Launch from Applications or Spotlight

## Build from Source

### Prerequisites

- Node.js 18+
- npm or yarn

### Steps

```bash
# Clone the repository
git clone https://github.com/AceVentura/messenger-app.git
cd messenger-app

# Install dependencies
npm install

# Run in development mode
npm start

# Build for production
npm run build
```

The built app will be in the `dist/` folder.

## Tech Stack

- [Electron](https://www.electronjs.org/) - Cross-platform desktop apps
- JavaScript/Node.js

## FAQ

### Is this the official Messenger app?
No, this is an unofficial wrapper around messenger.com. It's not affiliated with Meta/Facebook.

### Is it safe?
Yes. The app is signed and notarized by Apple. It simply loads messenger.com in a native window - no modifications to Messenger itself.

### Why use this instead of the browser?
- Dedicated app in your dock
- Separate from browser tabs
- Stays logged in
- Cleaner experience
- Less resource usage than a full browser

### Does it support voice/video calls?
Yes, all Messenger features work including voice and video calls.

### My login isn't persisting?
Make sure to quit the app with `Cmd+Q` (not just close the window) to save your session.

## Keywords

Facebook Messenger Mac, Messenger Desktop App, Messenger macOS, Facebook Chat Mac App, Messenger without browser, Standalone Messenger Mac, Messenger Mac download, Facebook Messenger native app, Messenger Electron app, Mac Messenger client

## License

MIT License - feel free to modify and distribute.

## Disclaimer

This project is not affiliated with, authorized, maintained, sponsored, or endorsed by Meta/Facebook or any of its affiliates or subsidiaries. This is an independent and unofficial app. Use at your own risk.

---

**Star this repo if you find it useful!**
