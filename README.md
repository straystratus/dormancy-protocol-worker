# DORMANCY protocol worker

This public repository provides the zero-cost GitHub Actions schedule for the
DORMANCY Solana rewards worker. The application source remains in a separate
private repository and is fetched with a dedicated read-only deploy key.

No private key or API token is committed here. Runtime secrets are stored as
encrypted GitHub Actions secrets. The release named `protocol-state` contains
only canonical data derived from the public Solana ledger.

The scheduled job is disabled until the verified DORMANCY mint, bonding curve
and deployment slot are added as repository variables after the pump.fun
launch.
Public zero-cost scheduler for the DORMANCY Solana rewards worker
