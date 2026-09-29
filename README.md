```markdown
# Threshold Batch Settlement

Complete batch settlement under threshold authorization on consortium blockchains.

## What it does
- Binds an approved manifest to indexed records, count, total, and expiry.
- Supports flat digest (B), full Merkle-root reconstruction (B2), and independent proofs (C).
- Guarantees complete, authorized, single-use settlement with ledger conservation.

## Results
- 92.09% lifecycle gas reduction at 1000 records vs. individual settlement.
- Independent proofs cost 157.75% more than direct batching.
- 810 workload observations, 225,720 successful lifecycle transactions, 68 adversarial cases.

## Stack
- Solidity 0.8.19
- FISCO-BCOS 3.7.3
- Python SDK

## License
MIT
```