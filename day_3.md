> solana address
F8GDLTAR5zbfdxi1KVFxT6Y1kZ5WMgfgyT8mCwsW7Gjg

> solana transaction-history $(solana address) --url devnet --limit 1
4CioqLSYFDTy9tzPFJxgrLUQraXuG4mdCUFsJAhBrAZGzGjXP1rUJqhxGCqkzCpN5Jgcp91XbqF7552TMLA5BUqe
1 transactions found

> solana confirm 4CioqLSYFDTy9tzPFJxgrLUQraXuG4mdCUFsJAhBrAZGzGjXP1rUJqhxGCqkzCpN5Jgcp91XbqF7552TMLA5BUqe -v --url devnet
RPC URL: https://api.devnet.solana.com
Default Signer Path: /home/shiv/.config/solana/id.json
Commitment: confirmed

Transaction executed in slot 457287321:
  Block Time: 2026-04-22T11:49:07+00:00
  Version: legacy
  Recent Blockhash: 4o9RWum9bDhNSfxsw78hCWQKYLWhiqLmG7rYAWxURDWr
  Signature 0: 4CioqLSYFDTy9tzPFJxgrLUQraXuG4mdCUFsJAhBrAZGzGjXP1rUJqhxGCqkzCpN5Jgcp91XbqF7552TMLA5BUqe
  Account 0: srw- devwuNsNYACyiEYxRNqMNseBpNnGfnd4ZwNHL7sphqv (fee payer)
  Account 1: -rw- F8GDLTAR5zbfdxi1KVFxT6Y1kZ5WMgfgyT8mCwsW7Gjg
  Account 2: -r-x 11111111111111111111111111111111
  Account 3: -r-x ComputeBudget111111111111111111111111111111
  Instruction 0
    Program:   11111111111111111111111111111111 (2)
    Account 0: devwuNsNYACyiEYxRNqMNseBpNnGfnd4ZwNHL7sphqv (0)
    Account 1: F8GDLTAR5zbfdxi1KVFxT6Y1kZ5WMgfgyT8mCwsW7Gjg (1)
    Transfer { lamports: 1000000000 }
  Instruction 1
    Program:   ComputeBudget111111111111111111111111111111 (3)
    Data: [3, 64, 66, 15, 0, 0, 0, 0, 0]
  Instruction 2
    Program:   ComputeBudget111111111111111111111111111111 (3)
    Data: [2, 239, 1, 0, 0]
  Status: Ok
    Fee: ◎0.000005495
    Account 0 balance: ◎319114.096816934 -> ◎319113.096811439
    Account 1 balance: ◎0 -> ◎1
    Account 2 balance: ◎0.000000001
    Account 3 balance: ◎0.000000001
  Compute Units Consumed: 450
  Log Messages:
    Program 11111111111111111111111111111111 invoke [1]
    Program 11111111111111111111111111111111 success
    Program ComputeBudget111111111111111111111111111111 invoke [1]
    Program ComputeBudget111111111111111111111111111111 success
    Program ComputeBudget111111111111111111111111111111 invoke [1]
    Program ComputeBudget111111111111111111111111111111 success

Finalized

