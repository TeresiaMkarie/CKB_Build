# Build a Simple Lock

**Name**: Teresia Mkarie<br>
**Date**: 3rd-August-2026<br>

## Tasks Completed

- **[Build a Simple Lock](https://docs.nervos.org/docs/dapp/simple-lock)**: Completed the full-stack dApp tutorial covering the ``hash-lock`` toy lock how script args store an expected hash, how the preimage is supplied via `WitnessArgs.lock`, and how CCC builds unlock transactions with `completeInputsByCapacity`, cell deps, and witness injection.
- **[Deploy a custom Lock Script]()**: Built the Script by compiling the contracts using **`pnpm install && pnpm build`**.Deployed the `hash-lock contract`

## Issues During Build
When building the contract discovered that you need a `CKB degugger` running the environment locally is not enough.
![build error](./pictures/hash_error.png)