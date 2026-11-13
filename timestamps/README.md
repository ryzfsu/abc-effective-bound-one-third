# Timestamps

[OpenTimestamps](https://opentimestamps.org) proofs for the assets of release `v1`.
Each proof commits to the SHA-256 of the file below and is anchored in Bitcoin block
975705 (2026-11-13 19:43:41 UTC).

| file | SHA-256 |
|---|---|
| `abc-effective-bound-one-third-v1.pdf` | `2d8ab6a89591755759fe1b8c2dc586ee2b57da20b8dc58dc370d73bc9e2d212e` |
| `abc-effective-bound-one-third-v1.tar.gz` | `f67b299c10fed47876038547530a1c88a1336e4f413f42ade9846001b8139462` |

To verify, download the release asset into this directory and run

    pip install opentimestamps-client
    ots verify timestamps/<file>.ots
