---
description: SQL table schema for polygon.token_mints and polygon.recent_token_mints
---

# polygon.token\_mints

Polygon ERC-20, ERC-721, and ERC-1155 token mints.

| Column Name        | Data Type         |
| ------------------ | ----------------- |
| `name`             | CHARACTER VARYING |
| `symbol`           | CHARACTER VARYING |
| `token_address`    | CHARACTER VARYING |
| `to_address`       | CHARACTER VARYING |
| `value`            | CHARACTER VARYING |
| `transaction_hash` | CHARACTER VARYING |
| `block_number`     | BIGINT            |
| `block_timestamp`  | BIGINT            |