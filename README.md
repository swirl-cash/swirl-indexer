# SWIRL Indexer

Incremental vault event indexer with atomic snapshots and reorganization recovery.

## Source layout

- `packages/indexer/src`: event scanning, persistence and read-only HTTP API.
- `packages/indexer/src/*.test.ts`: synchronization and API tests.

This is the component source snapshot of the tested SWIRL Protocol workspace. For the root dependency lockfile, integrated build and complete cross-component test flow, use [swirl-protocol](https://github.com/swirl-cash/swirl-protocol).

Never commit real private keys, recovery phrases, API credentials, server environment files or local service state. Public contract addresses, verification keys and proving artifacts are not account credentials.
