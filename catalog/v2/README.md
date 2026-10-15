# Library v2 rights sidecar — Preview

This independent signed extension preserves every byte of Catalog v1 and its six
collections. rights.json SchemaVersion 2, revision 1.0.0 binds the exact signed v1
SHA256 and all 29 resource IDs, versions, authors and package hashes. Six additional
unversioned built-in records document FROST, Obsidian and the four trusted renderers.

The existing pinned 3072-bit RSA-PSS/SHA256 key signs exact UTF-8 bytes. No private
key is stored here. rights.schema.json is documentation; clients validate locally
with a bounded strict parser, reject duplicate fields, and never fetch executable
policy. Old v1 clients ignore this sidecar and remain compatible.

Fourteen original MIT online motion presets have commercial-content approval with
NOTICE retention. Fifteen third-party cursor packages remain Needs Review for
Steam; observed site PD/CC BY declarations are provenance evidence, not independent
chain-of-title certification. Community availability, IDs and historical packages
are unchanged. No resource has been withdrawn in this revision.

Withdrawn versions block new v1.6 acquisitions; installed CUR/ANI and original
Windows backups must never be deleted by this metadata. Steam acquisition fails
closed when current verified commercial clearance is unavailable. Existing local
use remains offline capable. Steam SDK/AppID/SteamPipe/Cloud and platform acceptance
are not implemented. This metadata is not a Steam Ready claim.

See ../../reviews/commercial-v2/MATRIX.md and review-ledger.json for actual package
NOTICE digests, source-page hashes, observed licenses and review notes. Future rights
revisions use the main application's existing publish-library.ps1 -RightsOnly path,
not a second signer or a replacement v1 catalog.
