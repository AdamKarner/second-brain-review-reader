# Second Brain phone review reader

Public browser reader and public sample only. This repository contains no private cases, gold, predictions, model assets, reviewer notes or cryptographic secrets.

The reader creates non-exportable private keys on the reviewer's device and supports locally decrypting an explicitly approved encrypted review bundle. No encrypted bundle has been distributed by publishing this reader. The original committed draft remains unavailable in the current venue. Draft R2 is newly authored with new commitments, not a recovery or recreation of that original. Real review remains blocked until the owner approves encrypted delivery and independently reviews the gold.

The application uses no external scripts, fonts, analytics or application network requests. Its content security policy blocks outbound connections. Browser/device security and owner-controlled site code remain trust boundaries. Clearing browser storage destroys access to its non-exportable keys. This is an engineering prototype, not an audited secure-review product.

Public-fixture checks passed in Chromium at a 390×844 mobile viewport: sample interaction/layout, browser key storage, Python/browser RSA-OAEP and AES-GCM roundtrip, signed encrypted return and tamper rejection. No actual sealed cases or owner identity were used in testing.

This reader currently supports gold review only. It does not execute models, accept gold automatically, establish production safety, or provide a later prediction-review interface.

## Explicit draft revision R2

See `commitment-history.json` and `draft-r2-manifest.json` for the new commitments and retained original hash record. No private inference was recorded on the unavailable original draft. R2 has 100 answerable and100 unanswerable fresh synthetic engineering cases across ten10+10 categories; gold remains NOT_REVIEWED. Structural checks passed; they do not establish semantic gold correctness. The code uses the existing phone identity storage and does not require a new phone key. The encrypted package is prepared locally but has NOT been uploaded or transferred; publication of the empty reader does not authorize publishing ciphertext.
