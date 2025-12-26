# solana-resource-pool
Anchor based Solana program implementing a secure token pooling primitive with per-user accounting and enforced invariants.

Features:
  - Owns an SPL token vault (PDA)
  - Allows users to deposit tokens
  - Tracks balances per user in program-owned accounts
  - Allows withdrawals with strict validation
  - Emits events
