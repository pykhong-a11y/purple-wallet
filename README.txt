PURPLE WALLET - FIRST USABLE VERSION

What works:
- iPhone responsive lavender app
- Account balances with custom opening balances
- Income, expenses, transfers (transfers excluded from income/expense totals)
- Monthly budget, savings goals, history filters
- Device-local storage, offline access after first successful online installation
- Manual JSON backup export and restore

Not yet implemented:
- Automatic cloud backup (requires a cloud provider, user authentication, and secure database)
- Direct bank / Apple Pay integration, bank statement import, receipt import, recurring bills, charts
- Face ID/PIN or end-to-end encryption

IMPORTANT: Financial data is stored in browser localStorage on this device. It can be lost if Safari website data is cleared, the app is removed, or the device is reset. Export regular backups. Exported JSON files are NOT encrypted; store privately.

FREE HOSTING FROM IPHONE (GitHub Pages):
1. Create a free GitHub account at https://github.com (if needed).
2. Create a new PUBLIC repository called purple-wallet. WARNING: The source code will be public; never put personal financial data or passwords into the repository.
3. Upload the five files in this ZIP to the repository root (index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png). GitHub's mobile website may require 'Request Desktop Website' in Safari to access upload controls.
4. In repository Settings > Pages > Build and deployment, choose Deploy from a branch, main, / (root), Save.
5. Open https://YOUR-USERNAME.github.io/purple-wallet/ after Pages publishes (may take a few minutes).
6. In Safari, tap Share > Add to Home Screen > Add.
7. Launch Purple Wallet from your Home Screen. Open once with internet to cache the app, then it can run offline.

Note: GitHub Pages serves the PUBLIC app code only. Your transactions are not uploaded to GitHub; they stay on your device. For automatic encrypted cloud backups, a separate private backend is required.
