---
description: >-
  SQL table schema for goerli.beacon.voluntary_exits and
  goerli.beacon.recent_voluntary_exits
---

# goerli.beacon.voluntary\_exits

Goerli  table stores data about voluntary exits of validators from the Beacon Chain.

| Column Name       | Data Type         |
| ----------------- | ----------------- |
| `block_slot`      | DOUBLE            |
| `block_root`      | CHARACTER VARYING |
| `block_timestamp` | BIGINT            |
| `index`           | DOUBLE            |
| `epoch`           | DOUBLE            |
| `validator_index` | DOUBLE            |
| `signature`       | CHARACTER VARYING |