# Smart Kisti Manager v10.0

Complete Windows desktop application for Kisti and DPS accounting.

Features:
- Dashboard & collection analytics
- Customer management
- Kisti account management
- DPS savings management
- Payment history
- Due/overdue queue
- Reports
- CSV export for Excel/Google Sheets
- Local persistent JSON database
- Backup / Restore
- Printable reports
- Windows NSIS installer
- Portable EXE build
- Bengali interface

## Windows build
Run `INSTALLER-BUILD.bat`.

Or:
```bash
npm install
npm run build
```

The generated installer is in `dist/`.

## Windows 11 — GitHub থেকে Setup.exe
এই project-এ `.github/workflows/build-windows.yml` আছে। GitHub Actions ব্যবহার করে Windows runner-এ আসল NSIS Setup EXE compile হবে। তাই আপনার PC-তে Node.js/npm না থাকলেও GitHub থেকে build artifact হিসেবে Setup EXE পাওয়া যাবে।
