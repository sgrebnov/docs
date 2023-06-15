---
description: SQL table schema for polygon.tokens
---

# polygon.tokens

Polygon ERC-20, ERC-721 and ERC-1155 token contracts.

| Column Name       | Data Type         |
| ----------------- | ----------------- |
| `address`         | CHARACTER VARYING |
| `name`            | CHARACTER VARYING |
| `symbol`          | CHARACTER VARYING |
| `decimals`        | INTEGER           |
| `total_supply`    | CHARACTER VARYING |
| `is_erc20`        | BOOLEAN           |
| `is_erc721`       | BOOLEAN           |
| `is_erc1155`      | BOOLEAN           |
| `block_number`    | BIGINT            |
| `block_timestamp` | BIGINT            |
| `block_hash`      | CHARACTER VARYING |