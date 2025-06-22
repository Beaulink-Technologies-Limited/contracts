# Beaulink Contracts

Central, version-controlled source of truth for all **OpenAPI** and **Protocol Buffers** contracts.

* A **folder bump** (`v1` → `v2`) = breaking change.  
* Each Git tag marks a contract snapshot; services vendor the tag they’re compatible with.
* PRs touching `openapi/**` must pass **Spectral** linting (see workflow).
