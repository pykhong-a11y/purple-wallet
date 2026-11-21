PY’s Wallet v1.3 — Cream Edition

Features: account management, transactions, budgets, goals, backup, screenshot-text import via Apple Shortcuts.

Install: upload the six files to the root of your GitHub Pages repository, replacing the previous files. Keep the same repository URL and storage key. Export a backup before updating.

Shortcut: Create a shortcut with Take Screenshot, Extract Text from Image, URL Encode the extracted text, construct https://pykhong-a11y.github.io/purple-wallet/?ocr=ENCODED_TEXT and Open URLs. Replace ENCODED_TEXT with the encoded output variable. Set Settings > Accessibility > Touch > Back Tap > Double Tap to that shortcut.

Auto-save only when one distinct MYR amount, one recognized active account, and successful outgoing payment are identified. Uncertain captures remain pending. Duplicate identical OCR texts are rejected. Screenshots blocked by banks cannot be read.

Important: cloud backup, direct bank sync, Apple Pay integration, and fully automatic screenshot capture from ordinary Back Tap Screenshot are not available. The app stores data locally. Manual export is recommended.


V1.4 — Back Tap guided setup
- Open Capture in PY’s Wallet and use Set up Back Tap.
- The Open Apple Shortcuts button opens the iPhone Shortcuts app. It does NOT install a shortcut automatically.
- Follow the steps to build Take Screenshot → Extract Text from Image → URL Encode → Text (wallet URL + encoded text variable) → Open URLs.
- Assign the created shortcut to Double Tap in Settings → Accessibility → Touch → Back Tap.
- Apple iCloud Shortcut installation link requires creating and sharing an actual shortcut from an Apple device. No share link is bundled.
- Bank screenshot restrictions cannot be bypassed.


v1.5: Quick Add floating button on all screens. Quick Entry, Full Entry, Split Bill, Transfer, receipt photo selection (manual entry only), optional voice dictation where browser supports it. No automatic receipt OCR or cloud sync.


v1.6: Trip Albums, manual multi-currency conversion, claimable expenses, company reimbursements excluded from income, trip CSV export. Local data only; no automatic cloud backup or live exchange-rate feed. Existing storage key preserved.


v1.7: TNG receipt identification using TNGD/TNGOW, eWallet Balance confirmation, receipt date, duplicate check and retry of pending OCR captures.
