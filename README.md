# Second Brain phone review reader

Public browser reader and public sample only. This repository contains no private cases, gold, predictions, model assets, reviewer notes or cryptographic secrets.

The reader creates non-exportable private keys on the reviewer's device and supports locally decrypting an explicitly approved encrypted review bundle. No encrypted bundle has been distributed by publishing this reader. Real review remains blocked until the exact committed draft is recovered, recipient identity is confirmed, and the owner approves a confidential transfer mechanism.

The application uses no external scripts, fonts, analytics or application network requests. Its content security policy blocks outbound connections. Browser/device security and owner-controlled site code remain trust boundaries. Clearing browser storage destroys access to its non-exportable keys. This is an engineering prototype, not an audited secure-review product.

Public-fixture checks passed in Chromium at a 390×844 mobile viewport: sample interaction/layout, browser key storage, Python/browser RSA-OAEP and AES-GCM roundtrip, signed encrypted return and tamper rejection. No actual sealed cases or owner identity were used in testing.

This reader currently supports gold review only. It does not execute models, accept gold automatically, establish production safety, or provide a later prediction-review interface.
