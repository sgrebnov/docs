---
description: SQL table schema for eth.beacon.slots and eth.beacon.recent_slots
---

# eth.beacon.slots

Ethereum Beacon table contains data about each slot in the Beacon Chain.

<table><thead><tr><th width="471">Column Name</th><th>Data Type</th></tr></thead><tbody><tr><td><code>block_slot</code></td><td>DOUBLE</td></tr><tr><td><code>block_epoch</code></td><td>DOUBLE</td></tr><tr><td><code>block_timestamp</code></td><td>BIGINT</td></tr><tr><td><code>proposer_index</code></td><td>DOUBLE</td></tr><tr><td><code>skipped</code></td><td>BOOLEAN</td></tr><tr><td><code>block_root</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>parent_root</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>state_root</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>randao_reveal</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>graffiti</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>eth1_block_hash</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>eth1_deposit_root</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>eth1_deposit_count</code></td><td>DOUBLE</td></tr><tr><td><code>signature</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>attestations_count</code></td><td>DOUBLE</td></tr><tr><td><code>deposits_count</code></td><td>DOUBLE</td></tr><tr><td><code>proposer_slashings_count</code></td><td>DOUBLE</td></tr><tr><td><code>attester_slashings_count</code></td><td>DOUBLE</td></tr><tr><td><code>voluntary_exits_count</code></td><td>DOUBLE</td></tr><tr><td><code>sync_aggregate_sync_committee_bits</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>sync_aggregate_sync_committee_signature</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>execution_payload_block_number</code></td><td>DOUBLE</td></tr><tr><td><code>execution_payload_block_hash</code></td><td>CHARACTER VARYING</td></tr><tr><td><code>bls_to_execution_changes_count</code></td><td>DOUBLE</td></tr><tr><td><code>withdrawals_count</code></td><td>DOUBLE</td></tr></tbody></table>