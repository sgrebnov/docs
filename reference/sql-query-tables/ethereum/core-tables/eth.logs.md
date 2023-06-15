---
description: SQL table schema for eth.logs and eth.recent_logs
---

# eth.logs

Ethereum Transaction event logs.

| Column Name         | Data Type         |
| ------------------- | ----------------- |
| `log_index`         | BIGINT            |
| `transaction_hash`  | CHARACTER VARYING |
| `transaction_index` | BIGINT            |
| `address`           | CHARACTER VARYING |
| `data`              | CHARACTER VARYING |
| `topics`            | ANY               |
| `block_timestamp`   | BIGINT            |
| `block_hash`        | CHARACTER VARYING |
| `block_number`      | BIGINT            |