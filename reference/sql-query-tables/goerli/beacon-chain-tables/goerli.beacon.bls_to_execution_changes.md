---
description: >-
  SQL table schema for goerli.beacon.bls_to_execution_changes and
  goerli.beacon.recent_bls_to_execution_changes
---

# goerli.beacon.bls\_to\_execution\_changes

Goerli Beacon Chain requests to change old BLS withdrawal credentials to the new withdrawal credentials in execution address format.

| Column Name            | Data Type         |
| ---------------------- | ----------------- |
| `block_slot`           | DOUBLE            |
| `block_root`           | CHARACTER VARYING |
| `block_timestamp`      | BIGINT            |
| `validator_index`      | DOUBLE            |
| `from_bls_pubkey`      | CHARACTER VARYING |
| `to_execution_address` | CHARACTER VARYING |
| `signature`            | CHARACTER VARYING |