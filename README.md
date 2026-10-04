# Prism & Prism Lite

> **Note**: Prism Lite is a lightweight, widget-based icon theming solution for non-exploitable versions of iOS. It uses home screen widgets combined with private APIs (`LSApplicationWorkspace`) to launch applications directly without traditional URL scheme redirects.

 **Prism Lite is a stripped-down, barebones proof-of-concept version of Prism Full.** It contains bugs and is just a demonstration of what is possible.

---

## Features & Highlights

- **No URL Scheme Redirects**: Uses the private `LSApplicationWorkspace` API to launch apps cleanly, mimicking native app icons for the most part.
- **Widget-Based Theming**: Works on non-exploitable iOS versions without needing a jailbreak or low-level exploit.
- **LiveContainer Support**: Works with LiveContainer apps (note: LiveContainer apps *do* require redirects due to apps in it being launched via URL scheme).

---

## Installation & Sideloading

For widgets to sync and appear correctly, Prism Lite must be sideloaded with appropriate entitlements.

- **Recommended**: Sideload using **AltStore** or **SideStore**.
- **Troubleshooting**: If widgets are not appearing or syncing properly, ensure your sideloading tool has the necessary app/widget entitlements. Success may vary depending on the tool used. Restarting the app often helps.

---

## Frequently Asked Questions (FAQ)

### What happened to Prism (Full)?
Nothing! Everything intended for release was made available. Certain experimental features (like HTML lock screen clocks) were deemed too unreliable for daily use and had a high risk of being broken by Apple.

### Will Prism be open-sourced?
Yes, most likely. Work on the project will resume at a later date. If the full store and feature set are deprecated in favor of keeping it as just a widget icon themer, the entire codebase will be open-sourced.

### What happened to the original website and GitHub repository?
The original pages were taken down so everything could be consolidated and re-uploaded cleanly under this account. The custom website will not be returning.

### Does it use app redirects?
No. Standard app launching utilizes `LSApplicationWorkspace` to bypass web or scheme redirects. The only exception is **LiveContainer**, which inherently requires URL scheme redirects to function.

---
