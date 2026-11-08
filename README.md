# Second Brain phone review reader

Public browser reader, public sample, and the owner-approved recipient-encrypted R2 bundle. This repository contains no plaintext cases, gold, predictions, model assets, reviewer notes or unencrypted cryptographic secrets.

The reader creates non-exportable private keys on the reviewer's device and supports locally decrypting an explicitly approved encrypted review bundle. The initial empty reader publication included no bundle. The owner subsequently explicitly approved adding the encrypted R2 download; ciphertext is public and retained in Git history. The original committed draft remains unavailable in the current venue. Draft R2 is newly authored with new commitments, not a recovery or recreation of that original. Real review remains blocked until the owner approves encrypted delivery and independently reviews the gold.

The application uses no external scripts, fonts, analytics or application network requests. Its content security policy blocks outbound connections. Browser/device security and owner-controlled site code remain trust boundaries. Clearing browser storage destroys access to its non-exportable keys. This is an engineering prototype, not an audited secure-review product.

Public-fixture checks passed in Chromium at a 390×844 mobile viewport: sample interaction/layout, browser key storage, Python/browser RSA-OAEP and AES-GCM roundtrip, signed encrypted return and tamper rejection. No actual sealed cases or owner identity were used in testing.

This reader currently supports gold review only. It does not execute models, accept gold automatically, establish production safety, or provide a later prediction-review interface.

## Explicit draft revision R2

See `commitment-history.json` and `draft-r2-manifest.json` for the new commitments and retained original hash record. No private inference was recorded on the unavailable original draft. R2 has 100 answerable and100 unanswerable fresh synthetic engineering cases across ten10+10 categories; gold remains NOT_REVIEWED. Structural checks passed; they do not establish semantic gold correctness. The code uses the existing phone identity storage and does not require a new phone key. The owner separately approved publication of the encrypted R2 package. Its only public data file is `bundles/review-bundle-r2.encrypted.json`; plaintext and transport/private keys remain outside this repository.

## Owner-approved R2 download

Use the Download encrypted R2 bundle control on the page, save the file, select it and decrypt in the SAME browser that created the existing phone key. No new key setup is needed. Ciphertext SHA256: `73284403303adb229135804c98934c4370cfd0db163305e08ed5acc35989f24e`,317382bytes. No public plaintext cases/gold or private/AES keys are provided. The private transport key never leaves the evaluator venue. Gold remains NOT_REVIEWED; downloading or decryption is not review acceptance or permission to run inference.
