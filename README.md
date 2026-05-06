# Trading Journal

Personal mobile trading journal and P&L tracker — built as a PWA.

## Files

| File | Purpose |
|---|---|
| `index.html` | The full app |
| `manifest.json` | PWA manifest — enables "Add to Home Screen" |
| `sw.js` | Service worker — enables offline use |
| `icon-192.png` | App icon (home screen) |
| `icon-512.png` | App icon (splash screen) |

## Setup

1. Upload all files to this repository
2. Go to **Settings → Pages → Source: main branch / root**
3. Visit `https://yourusername.github.io/trading-journal` in Safari on iPhone
4. Tap **Share → Add to Home Screen**

## Data storage

All trade data is saved in your browser's localStorage — private to your device.
Use the **Backup & Restore** screen (↓ icon on dashboard) to export JSON backups regularly.
