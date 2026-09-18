# Wallet Activity Report — 0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045 (Ethereum mainnet)

**Report date:** 2026-07-15
**Scope:** Most recent ~10 outgoing (external) ETH transfers from the wallet above.
**Status:** ⛔ DATA UNAVAILABLE — do not merge until populated from a verified source.

## Data retrieval status

All attempts to retrieve the most recent outgoing transfers for this wallet failed:

- `alchemy_fetchTransfers` (eth-mainnet, `external`/`erc20` categories, multiple parameterizations, both upper- and lowercase address forms): returned **HTTP 403** on every attempt — the transfers endpoint is not accessible with the current API credentials.
- `alchemy_fetchAddressTransactionHistory` (eth-mainnet): returned **zero transactions** for this wallet. A control query against a high-volume third-party address also returned zero transactions, confirming that endpoint is not returning usable data either.

**No transfer data was retrieved, and none has been fabricated.** The table below is intentionally empty. This report must be regenerated from a working data source before it is used in the weekly review's provenance section.

## Outgoing transfers

| # | Recipient | Amount (ETH) | Tx Hash | Block |
|---|-----------|--------------|---------|-------|

*(No rows — data could not be retrieved. See "Data retrieval status" above.)*

### Row format (to be used once data is available)

Each line should read, in order: recipient address, amount transferred, transaction hash, and block number, e.g.:

```
1. Recipient: 0x…  |  Amount: 0.00 ETH  |  Tx: 0x…  |  Block: …
```

## Next steps

1. Restore or swap the data source (re-provision API credentials with transfer-endpoint access, or use an Etherscan CSV export for the address).
2. Re-run the outgoing-transfer retrieval for `0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045` on `eth-mainnet`.
3. Populate the table above with the last ~10 outgoing transfers and remove the status notice before merging into `main`.
