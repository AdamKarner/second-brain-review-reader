# Second Brain phone review reader

Public browser reader, public sample, and the owner-approved recipient-encrypted R2 gold and prediction-review bundles. This repository contains no plaintext cases, gold, predictions, model assets, reviewer notes or unencrypted cryptographic secrets.

The reader creates non-exportable private keys on the reviewer's device and supports locally decrypting an explicitly approved encrypted review bundle. The initial empty reader publication included no bundle. The owner subsequently explicitly approved adding the encrypted R2 download; ciphertext is public and retained in Git history. The original committed draft remains unavailable in the current venue. Draft R2 is newly authored with new commitments, not a recovery or recreation of that original. Gold review is complete and the first private run is frozen. Final source-support judgments remain pending through the separately owner-approved encrypted prediction-review bundle.

The application uses no external scripts, fonts, analytics or application network requests. Its content security policy blocks outbound connections. Browser/device security and owner-controlled site code remain trust boundaries. Clearing browser storage destroys access to its non-exportable keys. This is an engineering prototype, not an audited secure-review product.

Public-fixture checks passed in Chromium at a 390×844 mobile viewport: sample interaction/layout, browser key storage, Python/browser RSA-OAEP and AES-GCM roundtrip, signed encrypted return and tamper rejection. No actual sealed cases or owner identity were used in testing.

This reader supports separate gold and prediction reviews. It does not execute models, fabricate judgments, or establish production or device safety.

## Explicit draft revision R2

See `commitment-history.json` and `draft-r2-manifest.json` for the new commitments and retained original hash record. No private inference was recorded on the unavailable original draft. R2 has 100 answerable and100 unanswerable fresh synthetic engineering cases across ten10+10 categories; gold review was pending at authoring time; see review-status.json for the current accepted-gold status. Structural checks passed; they do not establish semantic gold correctness. The code uses the existing phone identity storage and does not require a new phone key. The owner separately approved publication of the encrypted R2 package. Its only public data file is `bundles/review-bundle-r2.encrypted.json`; plaintext and transport/private keys remain outside this repository.

## Owner-approved R2 download

Use the Download encrypted R2 bundle control on the page, save the file, select it and decrypt in the SAME browser that created the existing phone key. No new key setup is needed. Ciphertext SHA256: `73284403303adb229135804c98934c4370cfd0db163305e08ed5acc35989f24e`,317382bytes. No public plaintext cases/gold or private/AES keys are provided. The private transport key never leaves the evaluator venue. Gold review has since been independently accepted. Downloading/decryption alone is never review acceptance. The immutable first model run is complete; prediction-quality judgments remain pending.

## Owner-approved prediction review

The same existing phone key opens `bundles/prediction-bundle-r2.encrypted.json`. Ciphertext SHA256 `978403c021e397afa043ec7a92b25f3c874ba1db0097294e3ee8acb5be06b0f7`,378449bytes. Use the primary Download prediction review bundle button, select that file, and decrypt in the same browser/profile. Gold progress is retained separately and cannot substitute for prediction judgments. For each actual decision the reviewer explicitly supplies supported, disposition_valid, source_fresh, scope_valid and evidence_span_checked; there are no prefilled answers. At completion the reader signs and downloads encrypted-prediction-review.json, tied to immutable prediction digest `88607d9f8739c78fa2231bdd80f1a4d80642660dea2c956895e715ebe9a20556`. Return only the encrypted file, never case screenshots or plaintext notes. All private/AES keys remain outside this repository.

Current status is review-status.json. The frozen author manifest is retained unchanged as historical provenance; it does not describe current review completion. The first run yielded96 ANSWER and104 ABSTAIN decisions across200 cases, with190 model calls and10 over-window skips. These are output counts, not precision, coverage or accuracy. The unchanged public scorer is not run until final independent prediction judgments are validated. Six host operational probes remain NOT_RUN.

## Streamlined approved-gold reference decision

The owner challenged the duplicated full review. Exact source-bound comparison against the signed pre-inference gold found141 exact agreements (52 exact answer spans and89 correct abstentions),11 ANSWER decisions where approved gold requires abstention,15 missed approved answers, and33 other quoted spans still unadjudicated. Independent Node and Python UTF-16 implementations agreed. No first-result files or gold were changed; no model was rerun; no new manual prediction-review facts were fabricated.

The26 known reference decision mismatches mean that even if all33 other spans are valid, reference agreement is at most174/200 (87%). Strict exact-reference agreement is141/200 (70.5%); this is not a measured semantic accuracy score for all200. The11 wrong ANSWER dispositions already fail the proposed zero-erroneous-negative-answer screen. Reference screen NO_GO is conclusive without another complete manual review. Unsupported factual-claim rate remains unestablished: wrong dispositions are not automatically false facts.

See reference-result.json. The original frozen Forge independently reviewed-prediction score was NOT run with manufactured five-field rows. Original detailed-review controls and all browser progress are retained as an optional audit path; the default page now shows the reference result. Further variant adjudication would refine the answer-quality counts but cannot eliminate the26 reference decision mismatches. Six host operational probes remain NOT_RUN, and no activation/production/device acceptance is claimed. Earlier sections describe the historical full-review workflow, not a current requirement to repeat all200 cases.
